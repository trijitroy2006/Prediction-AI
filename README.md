# Prediction AI 🚀

An intelligent decision-support platform that leverages Machine Learning and AI to predict startup and project failure risks, conduct comprehensive market analysis, and generate actionable strategic mitigations.

## 🌟 Live Demo
To view the live application running on your local machine, run the following command and click the link:
**python -m streamlit run app_streamlit.py**
*(Then open [http://localhost:8501](http://localhost:8501) in your browser)*

---

## 🚀 Project Milestones Completed

### 📍 Milestone 1: Data Collection & Market Intelligence
The foundation of the platform, focusing on gathering core project parameters and contextualizing them within the broader market.
- **Project Submission Engine:** Seamless data ingestion for startup details, target market, budget, and business model.
- **Market Analysis Dashboards:** Algorithmic calculation of Total Addressable Market (TAM), Serviceable Available Market (SAM), and Serviceable Obtainable Market (SOM) with 5-year trend projections.
- **Competitor Landscape:** Dynamic identification of direct and indirect competitors, tracking market share, revenue, growth, and market positioning.

### 📍 Milestone 2: Risk Assessment & SWOT Analysis
Deep analytical evaluation of the submitted project to identify vulnerabilities.
- **Risk Scoring Algorithm:** Evaluates Team Capability, Financial Stability, Market Competition, Technological Feasibility, and Regulatory Risks.
- **Project Feasibility:** Generates a holistic percentage-based success probability score based on weighted risk metrics.
- **Automated SWOT Analysis:** Dynamically generates Strengths, Weaknesses, Opportunities, and Threats based on the startup's profile.

### 📍 Milestone 3: Recommendations & Strategic Reasoning
Advanced AI integration to move beyond identification and into actionable problem-solving.
- **AI Strategic Recommendations:** Integrates Large Language Models (Google Gemini API) to generate high-level strategic pivots and actionable advice.
- **Dynamic Risk Mitigation:** Categorized risk mitigation strategies (Financial, Market, Technical) with interactive UI filtering.
- **Agentic Workflows (LangGraph):** Implements an interactive multi-agent pipeline simulating Data Ingestion ➔ Risk Analysis ➔ Mitigation Strategy ➔ Final Reporting.
- **Zero-Config Database:** Fully migrated backend from PostgreSQL to a seamless local SQLite database (ml_project.db), enabling plug-and-play functionality without external server requirements.

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   \\\ash
   git clone https://github.com/trijitroy2006/Prediction-AI.git
   cd Prediction-AI
   \\\

2. **Create a virtual environment & install dependencies:**
   \\\ash
   python -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   \\\

3. **Environment Variables:**
   Create a .env file in the root directory and add your Google Gemini API key:
   \\\env
   GEMINI_API_KEY=your_actual_api_key_here
   \\\

4. **Run the Application:**
   \\\ash
   python -m streamlit run app_streamlit.py
   \\\

*(No database setup required! The app uses a zero-configuration SQLite database that will automatically initialize on your first run).*
