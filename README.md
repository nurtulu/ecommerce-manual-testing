# E-Commerce Manual Testing Project

A personal QA portfolio project demonstrating end-to-end manual testing skills — functional and negative testing, test case design, bug reporting, API testing, and browser-level (DevTools) analysis — performed against a public e-commerce demo application.

**Application under test:** [Practice Software Testing (Toolshop Demo)](https://practicesoftwaretesting.com)
**Status:** ✅ Completed

## Overview

This project simulates a complete, real-world manual QA engagement on an e-commerce web application. It covers five functional and technical areas: Login, Signup/Registration, Shopping Cart, REST API testing, and browser-level analysis via Chrome DevTools.

**Final results:** 73 test cases/checks executed, **89% overall pass rate**, **11 defects** identified and tracked to resolution-ready status on a Jira Cloud board.

| Area | Test Cases | Passed | Failed | Pass Rate |
|---|---|---|---|---|
| Login | 20 | 19 | 1 | 95% |
| Signup | 12 | 7 | 5 | 58% |
| Cart | 18 | 16 | 2 | 89% |
| API (Postman) | 13 | 13 | 0 | 100% |
| DevTools Analysis | 10 | 10 | 0 | 100% |
| **Total** | **73** | **65** | **8** | **89%** |

## Activities Performed

- Test planning (Test Plan document, EN + TR)
- Functional and negative testing
- Boundary Value Analysis & Equivalence Partitioning
- Manual test case design (16-column Excel template, bilingual EN/TR)
- Bug reporting with Severity (Critical/Major/Minor/Trivial) and Priority (High/Medium/Low) classification
- Defect tracking on a Jira Cloud Kanban board
- API testing with Postman (login, products, authenticated user profile, registration)
- Browser-level analysis with Chrome DevTools (Console errors/warnings, Network inspection, Lighthouse performance)
- Final Test Summary Report with defect statistics and conclusions (EN + TR)

## Project Structure

```
├── Test Plan/
│   ├── Test_Plan_EN.pdf
│   └── Test_Plan_TR.pdf
├── Test Cases/
│   ├── Login_Test_Cases.xlsx
│   ├── Signup_Test_Cases.xlsx
│   ├── Cart_Test_Cases.xlsx
│   ├── API_Test_Cases.xlsx
│   └── DevTools_Analysis.xlsx
├── Bug Reports/
│   ├── BUG-001.pdf ... BUG-011.pdf
├── API Testing/
│   └── Toolshop API Tests.postman_collection.json
├── Evidence/
│   └── Screenshots/
├── Test Summary Reports/
│   ├── Test_Summary_Report_EN.pdf
│   └── Test_Summary_Report_TR.pdf
└── README.md
```

## Bug Report Format

Each bug report includes: Bug ID, Title, Environment, Preconditions, Steps to Reproduce, Expected Result, Actual Result, Severity, Priority, Evidence, Related Test Case, and a linked Jira ticket.

All 11 bugs are also tracked in Jira: [E-Commerce Manual Testing board](https://nuronel.atlassian.net/jira/software/projects/KAN/boards/1) (tickets KAN-1 through KAN-12).

## Tools Used

Manual Testing · Postman · Chrome DevTools · Jira Cloud · Microsoft Excel · Microsoft Word/PDF · Git & GitHub

## Author

**Nur Önel** — Junior QA Engineer

---

# E-Ticaret Manuel Test Projesi

Bir e-ticaret demo uygulaması üzerinde gerçekleştirilen, uçtan uca manuel test becerilerini gösteren kişisel bir QA portföy projesi — fonksiyonel ve negatif test, test case tasarımı, hata raporlama, API testi ve tarayıcı seviyesinde (DevTools) analiz içerir.

**Test edilen uygulama:** [Practice Software Testing (Toolshop Demo)](https://practicesoftwaretesting.com)
**Durum:** ✅ Tamamlandı

## Genel Bakış

Bu proje, bir e-ticaret web uygulaması üzerinde gerçekleştirilen eksiksiz, gerçek dünyaya uygun bir manuel QA sürecini simüle eder. Beş fonksiyonel ve teknik alanı kapsar: Login, Signup/Kayıt, Alışveriş Sepeti, REST API testi ve Chrome DevTools üzerinden tarayıcı seviyesinde analiz.

**Sonuç:** 73 test case/kontrol çalıştırıldı, **%89 genel başarı oranı**, Jira Cloud board'unda çözüme hazır durumda takip edilen **11 hata** tespit edildi.

## Gerçekleştirilen Faaliyetler

- Test planlama (Test Planı dokümanı, EN + TR)
- Fonksiyonel ve negatif test
- Sınır Değer Analizi (BVA) ve Eşdeğerlik Sınıflandırması
- Manuel test case tasarımı (16 kolonlu Excel şablonu, EN/TR iki dilli)
- Severity (Critical/Major/Minor/Trivial) ve Priority (High/Medium/Low) sınıflandırmalı hata raporlama
- Jira Cloud Kanban board'unda hata takibi
- Postman ile API testi (giriş, ürünler, kimlik doğrulamalı kullanıcı profili, kayıt)
- Chrome DevTools ile tarayıcı seviyesinde analiz (Console hata/uyarıları, Network incelemesi, Lighthouse performansı)
- Hata istatistikleri ve sonuçlarıyla Test Özet Raporu (EN + TR)

## Kullanılan Araçlar

Manuel Test · Postman · Chrome DevTools · Jira Cloud · Microsoft Excel · Microsoft Word/PDF · Git & GitHub

## Hazırlayan

**Nur Önel** — Junior QA Engineer

