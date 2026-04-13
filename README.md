# 📊 PhonePe Payment Analytics — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-grey?style=flat-square&logo=powerbi&logoColor=black)
![Transactions](https://img.shields.io/badge/300K%20Transactions-1D9E75?style=flat-square)
![Volume](https://img.shields.io/badge/₹3.3B%20Volume-1D9E75?style=flat-square)
![Domain](https://img.shields.io/badge/FinTech%20%7C%20Payments-5C2D91?style=flat-square)

> **Server errors silently cause 34% of all payment failures — across every vertical, every month.**  
> This dashboard quantifies ₹102M in annual failed loan value and delivers 5 fixes engineering can act on today.

---

## 📸 Dashboard

![Homepage](Homepage.png)

🔗 [View Full Dashboard (PDF)](https://drive.google.com/file/d/19LSseQue7GsBeKZT_aEFRQLY3EQ82Jzj/view?usp=drive_link)

---

## 📌 Results at a Glance

| Metric | Value |
|--------|-------|
| Total transactions analysed | **300,000** |
| Total successful volume | **₹3,333M** |
| Overall failure rate | **4%** (12K transactions) |
| #1 failure cause | **Server errors — ~34% across all 5 verticals** |
| Highest-risk vertical | **Loans — ₹102M failed value annually** |
| Most stable vertical | **Bills & Recharge — <₹0.3M variance/month** |
| Peak demand months | **March (₹13.1M) and July (₹13.7M)** |

---

## 📂 Dashboard Pages

**🏦 Loans — highest value, highest risk**
![Loans](Loans.png)

**🛡️ Insurance — premium payment breakdown**
![Insurance](Insurance.png)

**💸 Money Transfer — all 4 UPI modes near-equal volume**
![Money Transfer](Money%20Transfer.png)

**🧾 Bills & Recharge — most operationally stable vertical**
![Bills and Recharge](Bills%20and%20Recharge.png)

---

## 🔍 The 3 Findings That Matter

**1. Server errors are a platform-wide crisis, not a product bug**
~34% of failures across every single vertical — Insurance, Loans, Money Transfer, Bills — are server errors. Same number, every page. This is infrastructure, not code.

**2. Loans carry 76% of total platform value at above-average risk**
₹2,532M flows through Loans. A 4.05% failure rate means ~₹102M lost annually. Fixing Loans reliability recovers more value than eliminating *all* failures in every other vertical combined.

**3. Wrong PIN is a UX problem, not a user problem**
27–34% of failures are wrong PIN entries — consistent across unrelated services. When the same error appears in Insurance, Loans, and Bills, the common variable is the interface, not the user.

---

## 🎯 Recommendations

| Priority | Action |
|----------|--------|
| 🔴 Critical | Fix server infrastructure — cut 34% failure share to under 15% |
| 🔴 Critical | Build Loans retry logic + multi-bank fallback — ₹102M at stake |
| 🟠 High | Add biometric / auto-fill PIN across all services |
| 🟠 High | Real-time alerts when server error rate exceeds threshold |
| 🟡 Medium | Pre-plan capacity for March & July demand spikes |

---

## 🛠️ Tools

| Tool | Purpose |
|------|---------|
| Power BI Desktop | 5-page dashboard, cross-table relationships, slicers |
| DAX | Success-filtered totals, failure rates, vertical comparisons |
| Power Query | Data loading, transformation across 5 service tables |
| Excel / CSV | Source data — 5 service-level transaction tables |

---

## 📁 Repository

```
PhonePe-Business-Intelligence-Dashboard/
├── 🖼️ Homepage.png
├── 🖼️ Loans.png
├── 🖼️ Insurance.png
├── 🖼️ Money Transfer.png
├── 🖼️ Bills and Recharge.png
├── 📄 pdf.pdf                 ← full dashboard export
└── README.md
```

---

## 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Seema%20Kumari-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/seema-kumari-375763308/)
[![Email](https://img.shields.io/badge/Email-seemakri136@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:seemakri136@gmail.com)
[![Portfolio](https://img.shields.io/badge/GitHub-seema--kri-181717?style=flat-square&logo=github)](https://github.com/seema-kri)

---

*5-page Power BI solution across 300K transactions — from raw payment logs to prioritised engineering recommendations.*
