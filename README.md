# FrozenFlow | Logistics Control Tower

An independent, interactive portfolio prototype by **VB (Venkateswararao Banday)**, inspired by the Head of Logistics & Warehousing vacancy at FreshAsia Foods, Erith, UK. It is not affiliated with or endorsed by FreshAsia.

## Run the app
Open `index.html` in a modern browser. No dependencies, server, API key or build process required.

## Publish on GitHub Pages
1. Create a new public GitHub repository, e.g. `frozenflow-control-tower`.
2. Upload `index.html`, `README.md` and `banner.png` to its root. The interview guide is optional; review it before publishing.
3. In Settings → Pages, choose Deploy from a branch, `main`, `/ (root)`, then Save.
4. Use the URL shown in Pages once deployment is complete.

## Modules
- Overview: calculated service, stock, costs and action indicators.
- Orders & POD: warehouse filter, search, quantity variance, exception checks and CSV export.
- 3PL scorecard: warehouse and carrier performance and governance cadence.
- Stock reconciliation: SAP versus WMS by SKU, batch and site; absolute variance, expiry and stock status.
- Cold chain: example temperature alerts, Quality disposition and partial batch trace exercise.
- Actions & recovery: add corrective actions, edit evidence, change status, enter verification evidence before closure and export CSV.
- Cost & claims: GBP budget variance, sample claims and interactive transport saving scenario.
- 90-day plan: stabilise, standardise and optimise; ownership and cross-functional handovers.
- Interview: CV-based evidence and practice questions.
- About: author, contact information and reset.

## KPI definitions and assumptions
Verified OTIF = on-time orders with exact quantity, correct product and verified POD / all sample orders. This is deliberately more conservative than conventional OTIF; agree the contractual definition before using it in practice. Order accuracy = orders with exact quantity and no recorded wrong-product exception / all sample orders. Stock line accuracy = exact matching SAP/WMS SKU-batch-site lines / all sample lines. Cost variance = actual minus budget. Targets of 98% verified OTIF, 99.5% order/stock accuracy and the −18°C alert threshold are illustrative, not FreshAsia targets or product-release criteria. Quality owns disposition. The small dataset is fictional and is not statistically representative.

## Design and limitations
Single-file HTML/CSS/JavaScript, responsive layout, no external dependencies. Corrective actions persist in browser localStorage if enabled; reset in About. The app is a demonstration, not a production system: no live SAP/WMS/TMS connections, authentication, shared data, immutable audit trail, complete batch genealogy or automated customer communications. Do not enter real customer, employee or operational data. Verification entries are user-entered, not independently authenticated. Claims and stock records are illustrative read-only examples. No actual company performance figures or logos are used.

## Suggested recruiter walkthrough
Start with Overview; filter East DC orders; compare provider scores; identify SKU-102 discrepancy; trace B102 and explain Quality hold; create a corrective action and show the verification workflow; demonstrate savings sensitivity; finish with the 90-day plan and candidate evidence.

## About the builder
**VB (Venkateswararao Banday)** is a multi-sector programme and operations leader with the right to work in the UK and India, looking for roles in London.

I build apps with AI and share them free to spread knowledge and useful information. If this helped you, and you know of any opportunity or can refer me, I would be very grateful.

[WhatsApp +91 9962507575](https://wa.me/919962507575) · [WhatsApp +44 7391 522993](https://wa.me/447391522993) · [LinkedIn](https://www.linkedin.com/in/venkateswararao-banday)

Prefer not to click links? WhatsApp +91 9962507575 · WhatsApp +44 7391 522993 · LinkedIn: linkedin.com/in/venkateswararao-banday

Source basis: supplied job description and candidate CV. No confidential company data included.
