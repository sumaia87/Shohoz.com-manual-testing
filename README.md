# 🚌 Shohoz.com — Manual Testing Project

A comprehensive manual testing project for **[Shohoz.com](https://www.shohoz.com)** — Bangladesh's leading online **bus, train, and air ticket** booking platform. This repository contains structured test cases, test plan, and bug report documentation for core user-facing features.

---

## 📋 Project Overview

| Detail | Info |
|---|---|
| 🌐 **Website** | [https://www.shohoz.com](https://www.shohoz.com) |
| 🧪 **Testing Type** | Manual / Black-Box / Functional |
| 🌍 **Browser** | Google Chrome (Latest) |
| 💻 **OS** | Windows 10 |
| 👩‍💻 **Tester** | Sumaia Akter |
| ✅ **Status** | Completed |

---

## 📊 Test Summary

| Module | Total Test Cases | ✅ Pass | ❌ Fail | Pass Rate |
|---|---|---|---|---|
| Homepage | 40 | 40 | 0 | ![100%](https://img.shields.io/badge/-100%25-brightgreen) |
| Create Account | 23 | 23 | 0 | ![100%](https://img.shields.io/badge/-100%25-brightgreen) |
| Login | 24 | 24 | 0 | ![100%](https://img.shields.io/badge/-100%25-brightgreen) |
| **Total** | **87** | **87** | **0** | **100%** |

---

## 📂 Test Documentation

> 📊 **View the full test case sheet directly in your browser (no download needed):**
>
> ### 👉 [Click here to view the Test Cases & Bug Report (Google Sheets)](https://docs.google.com/spreadsheets/d/1QWc3x2nRGwzhwcsSPEpyTGEfIygOaFaM/view)

---

## 🔍 Modules Tested

### 🏠 Homepage (40 Test Cases)

| Feature | Test Coverage |
|---|---|
| 🔝 Navbar | Logo redirect, menu navigation (Bus, Air, Train, Launch) |
| 🔍 Search Section | From/To fields, date picker, swap button, empty validation |
| 🖼️ Banner Section | Promotional banner visibility, link redirects |
| 🚌 Bus Booking Flow | Search results, filters, seat selection |
| 👤 Passenger Info | Form validation, payment page navigation |
| 🔗 Footer | Links, social media icons, app download buttons |

### 📝 Create Account (23 Test Cases)

| Field | Test Coverage |
|---|---|
| 👤 First Name / Last Name | Valid input, empty field, numeric rejection |
| 📱 Mobile Number | Valid format, invalid input, already registered |
| 📧 Email | Valid format, duplicate email, empty field |
| 🔒 Password | Minimum length, strength check, confirmation mismatch |
| 🖱️ Sign Up Button | Valid and invalid form submission behavior |

### 🔐 Login (24 Test Cases)

| Feature | Test Coverage |
|---|---|
| 📱 Mobile Number Field | Valid input, invalid format, empty validation |
| 🔒 Password Field | Input masking, visibility toggle |
| 🚪 Login Flow | Valid credentials, wrong password, CAPTCHA |
| 🔗 Other | Forgot password link, Remember Me, session persistence |

---

## 🐛 Bug Report

**4 bugs were identified** during this testing cycle across the Navbar and Registration Form modules.

| SL | Issue | Module | Priority | Severity |
|---|---|---|---|---|
| 01 | Navbar call button (Helpline 16374) is non-functional | Navbar / Header | 🟡 Medium | 🟡 Medium |
| 02 | First Name field accepts numbers, spaces & invalid characters | Registration Form | 🟡 Medium | 🟡 Medium |
| 03 | Last Name field accepts invalid characters, numbers & unnecessary spaces | Registration Form | 🟡 Medium | 🟡 Medium |
| 04 | Weak password (e.g. 12345678) is accepted during registration | Password Validation | 🔴 High | 🔴 High |

> 📄 Full bug details with reproduction steps are available in the `Bug_Report` sheet of the spreadsheet above.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| 📊 Microsoft Excel / Google Sheets | Test case documentation and bug reporting |
| 🌐 Google Chrome | Browser for manual testing |
| 🚌 Shohoz.com (Live) | Application under test |
| 🐙 GitHub | Version control and project hosting |

---

## 📁 Project Structure

```
shohoz-manual-testing/
├── README.md
└── shohoz_com_ManualTest.xlsx
    ├── Homepage          # 40 test cases
    ├── create account    # 23 test cases
    ├── Login             # 24 test cases
    ├── test_plan         # Full test plan
    ├── Bug_Report        # Bug tracking sheet
    └── Mind Map          # Feature mind map
```

---

