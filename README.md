# Saddle Up Bike Camp 2026 — Tools

Browser-based tools for running Saddle Up Bike Camp. Everything runs locally — no server, no login, no data leaves your machine. Open any HTML file directly in a browser, upload your spreadsheet, and print or save PDFs.

---

## Tools

### 🪪 Badge Generator — `badge_generator.html`

Generates ID badges for each camper, color-coded by session.

**Spreadsheet columns used:**
- Child's first and last name *(required)*
- Date of birth *(required)*
- Parent first and last name *(required)*
- Phone number *(required)*
- Hair color, eye color, age group, session *(optional)*

The tool also accepts a second spreadsheet with emergency contacts (up to 3 additional contacts per camper beyond the parent).

---

### 📋 Pre/Post Test Forms — `test_form_generator.html`

Generates landscape pre/post knowledge-test forms, grouped by session and age group, 5 campers per page.

**Spreadsheet columns used:**
- Child's first and last name *(required)*
- Age group, session *(optional — used for grouping)*

---

### 🎓 Completion Certificates — `completion_certificate_generator.html`

Generates one landscape completion certificate per camper, ready to print and sign.

**Spreadsheet columns used:**
- Child's first and last name *(required)*
- Session, age group *(optional)*

---

### 🚲 Adopt a Bike Gift Certificates — `bike_gift_certificate_generator.html`

Generates a 2-page PDF per qualifying camper: a gift certificate (page 1) and a liability waiver (page 2). Campers qualify if their bike field contains `50% Discount` or `Scholarship`.

Available in **English** or **Spanish** — select before generating.

**Spreadsheet columns used:**
- Child's first and last name *(required)*
- Bike / adopt field *(required — must contain `50% Discount` or `Scholarship`)*
- Session *(optional — used for filtering)*

---

### 📝 Drop-off / Pick-up Forms — `dropoff_pickup_form_generator.html`

Generates daily sign-in sheets for parent drop-off and pick-up — one page per session per day, five pages per session (Monday–Friday). Campers are listed alphabetically with blank signature columns for Drop-off and Pick-up.

**Spreadsheet columns used:**
- Child's first and last name *(required)*
- Session *(required — one form set generated per session)*

---

## How to use

All tools follow the same steps:

1. Open the HTML file in a browser (Chrome or Edge recommended for best PDF output).
2. Upload your camper spreadsheet (`.xlsx`, `.xls`, or `.csv`).
3. Map your column names to the fields the tool expects. Auto-detection handles most standard column names; the mapping saves as a default for future use.
4. Filter by session if needed.
5. Click **Generate**, then **Print / Save PDF** (or the per-camper **↓ PDF** buttons for gift certificates).

When saving as PDF from the print dialog, set margins to **None** and make sure **Background graphics** is enabled.

---

## Spreadsheet format

Any export from your registration system should work as-is. Column names don't need to match exactly — the tools auto-detect common variations and let you remap anything they miss. The column mapping can be saved as a default so you only need to set it once per tool.

---

## Sessions

Session colors used across all tools:

| Session | Color |
|---|---|
| June 22–26 Forest Grove | Green |
| June 29 – July 3 Forest Grove | Purple |
| July 6–10 Hillsboro UCC | Brown |
| July 13–17 Hillsboro UCC | Orange |
| July 20–24 Tigard Fanno Creek House | Blue |
| Aug 3–7 Hillsboro UCC | Violet |
| Aug 10–14 Hillsboro Tyson Rec Center | Dark Green |
| Aug 17–21 Hillsboro UCC | Navy |

---

*Saddle Up Bike Camp 2026 — WashCo Bikes*
