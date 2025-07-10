# 🧹 Lead List Cleaner (Data Cleaning Simulation)

This project simulates a real-world data entry and cleaning task where messy lead information is cleaned, validated, and formatted using Google Sheets.

---

## 📥 Input Data (Raw Leads)

| Field | Issues Simulated |
|-------|------------------|
| Name | Duplicates |
| Email | Uppercase, extra spaces, invalid formats |
| Phone | Mixed formats, dashes, brackets, empty rows |

---

## 🔧 Cleaned Output

Using formulas and logic in Google Sheets:

- ✅ Emails are trimmed and converted to lowercase  
  `=LOWER(TRIM(B2))`
- ✅ Phone numbers cleaned using regex:  
  `=REGEXREPLACE(TEXT(C2, "0"), "[^0-9]", "")`
- ✅ Highlights and blank handling for invalid fields
- ✅ Optional validation flag (valid/invalid phone)

---

## 🖼️ Screenshots

| Raw Leads | Cleaned Leads |
|-----------|----------------|
| <img width="1859" height="984" alt="image" src="https://github.com/user-attachments/assets/8e11113e-6273-4084-81e7-416c86f3297d" />
| <img width="1858" height="990" alt="image" src="https://github.com/user-attachments/assets/93ad23cd-461a-4bb4-ac03-221f906a2b31" />


---

## 📁 Files Included

- `lead-list-cleaner.xlsx` – Final downloadable sheet
- `raw-leads.png`, `cleaned-leads.png` – Proof of functionality

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Regex in spreadsheets
- Formula-based logic
- Real-world task simulation
