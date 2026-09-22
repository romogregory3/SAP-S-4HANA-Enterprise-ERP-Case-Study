# SAP-S-4HANA-Enterprise-ERP-Case-Study
Repository containing process documentation, transactional logs, and workflow diagrams for end-to-end SAP MM, PP, and FI/CO execution.
## Summary
This project demonstrates the configuration, execution, and validation of core enterprise business processes in SAP ERP. It covers the full lifecycle of Procure-to-Pay (P2P) and Plan-to-Produce, integrating Materials Management (MM), Production Planning (PP), and Financial Accounting & Controlling (FI/CO). Advanced automation features such as automated PO generation (ME59N), Evaluated Receipt Settlement (ERS), and EDI process workflows were implemented to streamline enterprise operations.
## 📌 Project Overview
- **Procure-to-Pay (P2P):** Vendor sourcing, RFQs, POs, 3-way invoice matching, stock transfers.
- **Plan-to-Produce:** SOP forecasting, MRP (`NETCH`), BOM explosion, production order settlement.
- **Process Automation:** Auto-PO creation (`ME59N`), Evaluated Receipt Settlement (`ERS/MRRL`), and EDI/IDoc workflows.

## 🛠️ Key SAP Transactions & Objects
- **MM:** `ME51N`, `ME41`, `ME21N`, `MIGO`, `MIRO`
- **PP:** `MC88`, `MD02`, `MD05`, `CO01`, `CO15`, `CO88`
- **Automation:** `ME59N`, `MRRL`

## 📊 Process Architecture
See `/diagrams/` folder for EDI/IDoc flowcharts and MRP multi-level BOM explosion analysis.

### 📸 Proof of System Execution
- [View Goods Receipt & Quality Transfer Documentation](./docs/MM_Goods_Receipt.pdf)
- [View MRP Run & Production Order Settlement Logs](./docs/PP_Production_Execution.pdf)
