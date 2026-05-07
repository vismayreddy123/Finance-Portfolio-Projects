# Fund Operations Trade Reconciliation Framework

Excel-based reconciliation system demonstrating fund operations processes used in hedge fund middle offices.

## 📊 Project Overview

This framework automates the daily reconciliation process between internal trade records and external broker confirmations, identifying discrepancies that require operational resolution.

**Key Metric:** 82% clean reconciliation rate across 100 trades

## 🔧 Features

- **100 internal trade records** across 10 trading days
- **98 external broker confirmations** with intentional test breaks
- **Automated XLOOKUP matching** by security
- **Break detection system** identifying:
  - Quantity mismatches (8 breaks)
  - Price discrepancies (5 breaks)
  - Status conflicts (1 break)
  - Missing trades (4 breaks)
- **Executive dashboard** with color-coded metrics
- **102-security master data** with sector classifications
- **Break resolution guidelines** with SLAs and escalation procedures

## 💼 Skills Demonstrated

**Excel:** XLOOKUP, COUNTIF, Conditional Formatting, Data Validation, Dashboard Design

**Fund Operations:** Trade lifecycle (T+0 to T+2), Reconciliation processes, NAV calculation, Break management, Exception reporting

## 📁 Components

- **README Sheet:** Project documentation
- **Internal_Trades:** Firm's internal trade records
- **Broker_Confirms:** External broker confirmations
- **Reconciliation:** Automated matching and break detection logic
- **Dashboard:** Executive summary with metrics
- **Reference:** Security master data and resolution guidelines

## 📄 Documentation

**[Technical Report](Fund_Reconciliation_Technical_Report.pdf)** - Comprehensive 4-page documentation covering:
- Technical architecture and design decisions
- Formula logic and implementation details
- Fund operations context and real-world applications
- Key terminology and operational procedures
- Break resolution guidelines and SLAs

## 🎯 Real-World Application

This framework models the reconciliation processes used by middle office teams at hedge funds and asset managers to ensure accurate position keeping, NAV calculation, and regulatory compliance.

## 👤 Author

**Vismay Somi Reddy**  
Finance & Business Management Graduate  
[LinkedIn](https://www.linkedin.com/in/vismay-reddy-7b8311229)

---

*Sample data used for demonstration purposes*
