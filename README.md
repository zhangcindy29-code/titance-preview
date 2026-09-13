# Titance Legal — 案件与合规平台 · 演示

A demonstration interface for a matter management and AML/CTF compliance
workbench built for an Australian conveyancing practice.

**This is a design demonstration only.** All clients, properties, matter
numbers, documents and correspondence shown are fictitious examples created
for illustration. No real client data appears anywhere in this repository.

## 功能演示 / What it shows

- **待归档邮件 / Unfiled mail** — inbound correspondence filed to its matter.
  Mail carrying a matter number is filed on an exact match; everything else is
  suggested and must be confirmed by the fee earner.
- **案卷文件 / Matter documents** — files grouped by conveyancing stage, with
  outstanding statutory documents flagged against the cooling-off deadline.
- **反洗钱档案 / AML record** — customer due diligence with an append-only
  audit log, exportable as an evidence pack.
- **垫付支出 / Disbursements** — per-matter search costs and on-charge status.

中英双语，右上角切换。Bilingual — switch at top right.

## 技术 / Technical

Single self-contained HTML file. No build step, no dependencies beyond Google
Fonts. Served via GitHub Pages.
