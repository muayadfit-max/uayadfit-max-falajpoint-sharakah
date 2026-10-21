# # FalajPoint Sharakah Partnership Canvas

I understand you need an interactive presentation canvas for tomorrow's FalajPoint–Sharakah

_Started 2026-10-21 13:02 UTC_

---

## User

Situation: FalajPoint (Omani specialist consultancy in minerals, fertilizers, and industrial process & water systems) has a meeting tomorrow with Sharakah. Sharakah is Oman’s long-standing SME development and Hybrid Venture Capital organization (established by Royal Decree in 1998). They combine term financing, working capital, Sharia-compliant structures, and equity (Sharakah Ventures pre-seed/seed and growth equity). Their model focuses on funding, capacity building, corporate partnerships, and promoting entrepreneurship culture.

Goal: Create a clean, professional interactive canvas for the meeting. The visual concept is a single continuous orange line (FalajPoint primary orange #FF5B05) with three clearly marked clickable points along it. When the user clicks a point, a detailed slide/panel opens for that topic. The user can collapse the panel and click another point to open a different slide. The third point’s slide (or a clean closing state) must include a QR code that links to FalajPoint’s company profile PDF.

Theme colors:
- Primary Orange: #FF5B05
- Primary Deep Teal: #075055
- Clean, elegant, consultancy aesthetic with strong typography and generous whitespace. Avoid clutter.

Three points and the content that should appear when each is clicked:

1. End-to-end Startup & SME Event Organization
We remove the operational stress so Sharakah can focus on funding and ecosystem building. Full A-to-Z management including:
- Defining clear objectives and audience
- Agenda design and professional facilitation
- Creating clear, well-structured PowerPoints that accurately represent their content and brand
- Selecting the right venue
- Logistics, AV, branding, on-site coordination, and follow-up

Case study to highlight: Ministry of Energy & Minerals workshop “Roadmap for Integration Between Minerals, Fertiliser, and Chemicals in the Sultanate of Oman”, held under the patronage of Undersecretary Eng. Mohsen Al-Hadhrami. The workshop was built on a study prepared by FalajPoint linking mineral resources (gypsum, limestone, dolomite, laterite, kaolin, potash, etc.) with fertilizer and chemical manufacturing capabilities, infrastructure, and markets to support local content and Oman Vision 2040. The Sharakah team was invited and observed how the event was delivered.

2. Financial Services that support investment decisions
From FalajPoint’s capabilities:
- Accounting & bookkeeping
- Audit & assurance
- Financial advisory (budgets, forecasts, OPEX tracking)
- Risk & internal controls
- Tax (direct & indirect / VAT)
- Feasibility studies and bankable investment cases / financial models

Position this as “the control layer — numbers that stand behind the engineering.” Relevant for Sharakah’s portfolio companies, due diligence, and growth support.

3. Fertilizers, Minerals & Process Consultancy + Investor Readiness
- Specialized consultancy in fertilizers, chemicals, minerals, process systems, and water treatment.
- Support existing portfolio companies or fill technical gaps in these sectors.
- Prepare professional investor materials (teasers, presentations, and financial models) so Sharakah’s startups can raise additional funding from other investors.

On the third slide (or as a clean final element), generate a QR code that points to the company profile PDF using this Google Drive link: https://drive.google.com/file/d/1DRMjnPYOukhLQNgcAoR4fgWLZwbTsavb/view?usp=sharing

Output: A polished interactive canvas ready for presentation. Keep the interaction simple and reliable (click point → open panel, collapse → switch to another point). Use the orange line as the clear visual spine. Make the content concise, professional, and suitable for a senior Sharakah audience.

## Assistant

_[tool: list_files]_

_[tool: dc_write]_

_[tool: ready_for_verification]_

I've built the meeting canvas. A single orange line runs across the screen with three numbered points on it. Clicking a point moves the line up to the top as a nav bar and slides that topic's panel up from below. You can switch points from the line, step through with Previous/Next, or collapse back to the opening view.

- **Keyboard:** 1, 2 and 3 open each point, the arrow keys step between them, and Esc collapses.
- **QR code:** It's on point 3 and links to the company profile PDF on Google Drive. The code is drawn in deep teal, and both the code and the "Open profile" link are clickable. Scan it with a phone before the meeting. The Drive file also needs to be shared as "Anyone with the link", or the scan will hit a sign-in page.
- **Settings:** In the Tweaks panel you can hide the keyboard hint, or set the canvas to open on a specific point.
- **Fonts:** The attached design system was empty, so I used your two colours with Instrument Serif and Instrument Sans.

The canvas needs an internet connection to load the fonts and draw the QR code. I can save it as a single offline file if the meeting room might not have reliable internet.

## User

Found issues — fixing…

## Assistant

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_html_str_replace]_

_[tool: dc_js_str_replace]_

_[tool: ready_for_verification]_

I've fixed all four layout problems; a second check is running now.

- **Point labels:** they now get narrower on small screens, so the three captions no longer run into each other.
- **Opening headline:** it now scales with screen height as well as width, so it stays clear of the orange line on shorter screens.
- **Open panel:** the sideways scrollbar is gone.
- **QR code:** it no longer tries to load a broken image while the page is still opening, so that console error is gone.

