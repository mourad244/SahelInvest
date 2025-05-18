# 🪙 Sahl Invest

**Sahl Invest** is a minimalist, AI-powered SaaS application designed for **beginner investors** to analyze stocks listed on the **Moroccan Stock Exchange** (with global markets coming soon). Users can upload financial reports manually **or let the app automatically retrieve the latest company PDFs** from official sources. It extracts key metrics like **P/E ratio, revenue, debt, dividends**, and provides **simple AI-powered summaries** in **Arabic, French, and English** — to help make confident, long-term investment decisions.

---

## 🌍 Key Features

- 📄 **PDF Upload & Scraping** – Upload reports manually *or let the app automatically fetch them* from official Moroccan sources (e.g. Casablanca Stock Exchange, AMMC).
- 🔍 **Data Extraction Engine** – Extracts financial data from PDFs using advanced NLP + OCR (even scanned files).
- 🧠 **AI-Powered Insights** – Generates beginner-friendly analysis on whether a stock is worth considering.
- 📊 **Core Financial Metrics** – P/E ratio, revenue growth, debt levels, dividends, etc.
- 🈂️ **Multilingual Support** – Full UI and analysis in **English, French, and Arabic**.
- 💸 **Affordable Subscription** – Just **10 Dhs/month** to access all features.

---



## 🔧 Tech Stack

| Layer            | Technologies                                                     |
|------------------|------------------------------------------------------------------|
| Frontend         | React + Vite + TailwindCSS                                       |
| Backend          | FastAPI or Django (Python)                                       |
| PDF Parsing      | PyMuPDF, PDFPlumber, Camelot, Tesseract OCR                      |
| AI / NLP         | Scikit-learn, HuggingFace Transformers (FinBERT), OpenAI         |
| Scraping         | BeautifulSoup, Requests, Puppeteer (optional for JS-heavy sites) |
| Database         | PostgreSQL                                                       |
| Infrastructure   | Docker, GitHub Actions (CI), Render/Heroku (MVP)                 |

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/SahlInvest.git
cd SahlInvest
```

2. Backend Setup (FastAPI Example)
```bash
cd backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

## 🧪 Features in Progress
<!-- like a checklist -->

- [x] Manual PDF upload

- [x] PDF data extraction (P/E, debt, revenue, dividends)

- [x] Multilingual UI (Arabic, French, English)

- [ ] AI-generated stock summary and risk analysis

- [ ] Web scraping from Moroccan stock exchange & company websites

- [ ] Auto-alert when new reports are published

- [ ] Expand to global markets (US, Europe, etc.)

## 📁 Project Structure

```
SahlInvest/
│
├── frontend/        # React + Vite + i18n
├── backend/         # FastAPI or Django app
├── scripts/         # PDF parsing, scraping, and AI modules
├── data/            # Sample PDFs & test results
└── docs/            # Project documentation
```

## 📣 Why Sahl Invest?

"Sahl" (سهل) means easy in Arabic.

Our mission is to simplify stock analysis for everyone — in your language, with your budget, and with full AI support.

---

## 🤝 Contributing

We welcome contributions from anyone interested in making stock analysis easier for everyone.

- Fork the repo
- Create a feature branch
- Submit a pull request

## 📬 Contact

For any questions or feedback, please contact us at [mouradiservicex@gmail.com](mailto:mouradiservicex@gmail.com).