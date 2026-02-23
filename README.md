# 🛒 OpenCart E-Commerce — Manual Testing Project

> **A comprehensive manual QA testing project for the [OpenCart Demo](https://demo.opencart.com/) e-commerce platform, covering 8 modules, 200+ test cases, and 11 documented bugs.**

---

## 📌 Project Overview

This project documents a full manual black-box testing effort performed on the OpenCart e-commerce demo application. The goal was to validate core user flows, identify defects, and produce professional QA artifacts including test scenarios, detailed test cases, and structured bug reports.

| Item | Details |
|------|---------|
| **Application Under Test** | OpenCart Demo |
| **URL** | https://demo.opencart.com/ |
| **Testing Type** | Manual Black-Box Testing |
| **Test Environment** | Windows 10 · Chrome v142 |
| **Total Modules Tested** | 8 |
| **Total Test Cases** | 200+ |
| **Bugs Found** | 11 |
| **Documentation Format** | Microsoft Excel (.xlsx) · Word (.docx) |

---

## 🗂️ Modules Tested

| # | Module | Test Cases | Valid | Negative | Bugs |
|---|--------|-----------|-------|----------|------|
| 1 | 🏠 Homepage | 55 | 55 | 0 | 2 |
| 2 | 📝 Register Account | 45 | 23 | 22 | 0 |
| 3 | 🔐 Login Account | 29 | 20 | 9 | 0 |
| 4 | 🔍 Search Box | 25 | 17 | 8 | 5 |
| 5 | 📦 Product Detail Page | 34 | 24 | 10 | 4 |
| 6 | 🛒 Add to Cart | 24 | 16 | 8 | 0 |
| 7 | 💳 Checkout | 15 | — | — | 0 |
| 8 | 📋 Product Listing | 15 | — | — | 0 |
| | **Total** | **200+** | **155+** | **57+** | **11** |

---

## 📁 Repository Structure
```
📦 OpenCart-Manual-Testing
├── 📂 Test-Scenarios
│   ├── homepage_test_scenarios.xlsx
│   ├── register_account_test_scenarios.xlsx
│   ├── login_account_test_scenarios.xlsx
│   ├── search_test_scenarios.xlsx
│   ├── product_test_scenarios.xlsx
│   ├── add_to_cart_test_scenarios.xlsx
│   ├── checkout_test_scenarios.xlsx
│   └── product_list_test_scenarios.xlsx
│
├── 📂 Test-Cases
│   ├── homepage_test_cases.xlsx
│   ├── register_account_test_cases.xlsx
│   ├── login_account_test_cases.xlsx
│   ├── search_test_cases.xlsx
│   ├── product_detail_test_cases.xlsx
│   └── add_to_cart_test_cases.xlsx
│
├── 📂 Bug-Reports
│   ├── homepage_bug_report.xlsx
│   ├── search_box_bug_report.xlsx
│   └── product_detail_bug_report.xlsx
│
└── README.md
```

---

## 🧪 Test Case Structure

Each test case was written with the following fields:

| Field | Description |
|-------|-------------|
| **Test Case ID** | Unique identifier (e.g., `TC-HP-001`) |
| **Scenario ID** | Linked scenario (e.g., `HP-001`) |
| **Test Case Title** | Clear description of what is being tested |
| **Preconditions** | State required before test execution |
| **Test Steps** | Numbered, step-by-step instructions |
| **Expected Result** | What the system should do |
| **Actual Result** | What actually happened during execution |
| **Status** | Not Executed / Pass / Fail / Blocked |
| **Priority** | High / Medium / Low |
| **Test Type** | Functional / Negative |

---

## 🐞 Bugs Found

### Homepage Bugs

| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BUG-001 | Desktops category page displays unrelated products (Cameras, Monitors) | 🔴 Major | Open |
| BUG-002 | Laptops & Notebooks sub-categories show 0 products despite main category working | 🔴 Major | Open |

---

### Search Box Bugs

| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BR-SEARCH-REL-01 | Search returns incomplete results for general keywords | 🔴 High | Open |
| BR-SEARCH-ACC-01 | Search returns incomplete results for exact/partial product names | 🔴 High | Open |
| BR-SEARCH-AUTO-01 | Autocomplete/suggestions not working when typing | 🟠 Medium | Open |
| BR-SEARCH-CHAR-01 | Search box does not accept or handle special characters | 🟠 Medium | Open |
| BR-SEARCH-EMP-01 | Empty/blank input and misspelled words not handled properly | 🟠 Medium | Open |

---

### Product Detail Page Bugs

| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BR-PD-ZOOM-01 | Product image zoom functionality not enabled on hover | 🔴 High | Open |
| BR-PD-AVAIL-01 | Product availability status not displayed on product page | 🟠 Medium | Open |
| BR-PD-REV-01 | Review "Continue" button not functional — cannot submit reviews | 🔴 High | Open |
| BR-PD-CAT-01 | "Show All" category filter displays all site products instead of category-specific | 🔴 High | Open |

---

## 🐛 Bug Report Structure

Each bug was documented with the following fields:

| Field | Description |
|-------|-------------|
| **Bug ID** | Unique identifier (e.g., `BR-SEARCH-AUTO-01`) |
| **Related Test Case** | The test case that revealed the bug |
| **Bug Title** | Clear, concise description of the defect |
| **Environment** | OS + Browser + Version |
| **Severity** | Critical / Major / Medium / Minor |
| **Priority** | High / Medium / Low |
| **Status** | Open / In Progress / Resolved / Closed |
| **Steps to Reproduce** | Exact numbered steps |
| **Expected Result** | What should happen |
| **Actual Result** | What actually happened |
| **Root Cause / Notes** | Analysis and possible cause |

---

## ✅ Types of Testing Applied

| Testing Type | Description | Applied To |
|-------------|-------------|------------|
| **Functional Testing** | Validates features work as expected | All modules |
| **Negative Testing** | Tests with invalid/unexpected inputs | All modules |
| **UI Testing** | Verifies layout, buttons, and navigation | Homepage, Product Page |
| **Boundary Value Analysis** | Tests at min/max input limits | Register, Search |
| **Equivalence Partitioning** | Groups valid/invalid input ranges | Register, Login |
| **Security Testing** | Tests SQL injection and XSS inputs | Search Box |
| **End-to-End Testing** | Tests complete user journey | Cart → Checkout |

---

## 🔑 Key Skills Demonstrated

- ✅ Writing clear, structured **test scenarios** from feature requirements
- ✅ Designing **positive and negative test cases** for full coverage
- ✅ Identifying **boundary conditions** and **edge cases**
- ✅ Logging professional **bug reports** with reproduction steps and root cause analysis
- ✅ Applying **test design techniques** (BVA, EP, Decision Tables)
- ✅ Testing for **security vulnerabilities** (XSS, SQL Injection)
- ✅ Organizing and maintaining **QA documentation** in Excel

---

## 🌐 Application Under Test

The OpenCart Demo is a fully functional e-commerce platform used for testing purposes.

**Key Features Tested:**
- User Registration & Authentication
- Product browsing, search, and filtering
- Shopping cart management
- Checkout flow
- Product reviews and ratings
- Wishlist and product comparison

**Demo URL:** https://demo.opencart.com/

---
