# 🧪 Data Alchemist - AI-Powered Resource Allocation Configurator

## 🚀 Project Overview

**Data Alchemist** is a hybrid AI-enabled web tool designed to help non-technical users clean, validate, and configure complex resource allocation data. It helps eliminate spreadsheet chaos by enabling uploads of CSV/XLSX files for Clients, Workers, and Tasks, and provides real-time validation, rule configuration, AI suggestions, and export features.

### 🌐 Tech Stack

| Layer      | Technology                      |
|------------|----------------------------------|
| Backend    | FastAPI (Python)                 |
| AI/NLP     | OpenAI API (via FastAPI)         |
| Data       | Pandas, openpyxl, Pydantic       |
| Frontend   | Minimal Next.js (TypeScript)     |
| UI Styling | Tailwind CSS (optional)          |
| Deployment | FastAPI: Render/HuggingFace<br>Next.js: Vercel |

---

## 🎯 Goals

- Upload and parse CSV/XLSX data for clients, workers, and tasks.
- View and edit the data in a web-based grid (inline editing).
- Run real-time validations and display summaries/errors.
- Accept natural language queries and rule creation commands.
- AI-assisted validation, rule suggestions, and data fixes.
- Export clean data and a rules.json file.

---

## ✅ Key Features

- 📤 Upload 3 entity files (`clients.csv`, `workers.csv`, `tasks.csv`)
- 🧠 AI-powered validation and rule suggestions
- 📝 Natural language queries and corrections
- 🧩 Rule input UI and natural language to rules converter
- 📊 Prioritization via sliders or drag-and-drop
- 📦 Export validated files and `rules.json`

---

## 🗺️ Roadmap

### ✅ Milestone 1: Core Data Handling (Day 1)
- [ ] Setup FastAPI backend
- [ ] API for file upload & parsing (CSV/XLSX)
- [ ] API for data validation (basic rules)
- [ ] API to return cleaned data
- [ ] API to export cleaned CSVs + JSON

### ✅ Milestone 2: Minimal Frontend (Day 1 Evening - Day 2)
- [ ] Setup Next.js frontend with TypeScript
- [ ] Upload interface for files
- [ ] View tables using simple components
- [ ] Show validation results and status
- [ ] Trigger backend rules and validation

### ✅ Milestone 3: AI Integration + Export (Day 2)
- [ ] Connect OpenAI API for:
  - [ ] Header auto-mapping
  - [ ] Rule generation from text
  - [ ] Natural language queries
- [ ] Export as `.zip`: Cleaned CSVs + `rules.json`
- [ ] Deploy both frontend and backend
- [ ] Include `/samples` folder with input files

---

## 🧪 Submission Checklist

- [ ] Public GitHub repo with code
- [ ] `samples/` folder with example data
- [ ] Hosted frontend on Vercel
- [ ] Hosted backend on Render/HuggingFace
- [ ] Clean README + optional demo video

---

## 👤 Author

Shreshtha Kumar Gupta  
Built with Python (FastAPI) and Next.js  
