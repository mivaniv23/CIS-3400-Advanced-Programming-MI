# CIS 3400 – Advanced Programming
## Project 2: Python Application Development

**Student Name:** Markiian Ivaniv
**Project Title:** Budget-Expense Management Application
**Course:** CIS 3400 – Advanced Programming  
**Final Presentation:** December 8, 2026

---

## 1. Project Overview

**Application Name:** [Name]

**Project Option:** Database-Enabled

### Problem Statement
The Catawba College Solar Vehicle Team needs an organized way to manage its project budget and track expenses. Currently, managing purchases, receipts, and spending across different team departments can become difficult, especially as the team develops multiple solar vehicles. This application provides a centralized system for recording expenses, monitoring the remaining budget, and organizing financial information. It also allows the team to generate Excel reports, making financial tracking and reporting easier and more efficient.

### Intended Users
The primary users are members of the Catawba College Solar Vehicle Team, especially team leadership and members responsible for purchasing, finances, and project management.

Users will be able to:

- Monitor the team's overall budget.

- Record and organize purchases.

- Upload and access expense receipts.

- Track spending across different departments.

- Generate financial reports for specific periods.

- Review how much money remains available.

### Unique Features
Unlike a basic expense calculator or classroom budgeting demonstration, this application is designed specifically for a university solar vehicle team.

Its main distinguishing features include:

- Department-based expense tracking for Mechanical, Electrical, Media, Operations, and Travel.

- Receipt image uploads connected to individual transactions.

- A centralized SQLite database that preserves financial records.

- Automatic budget calculations and spending summaries.

- Professional Excel reports with transaction details and category summaries.

- The application is designed around the actual financial management needs of a student engineering team.

## 2. Application Features

- **Feature 1: Budget Dashboard:** [Displays the total team budget, total expenses, remaining balance, and percentage of the budget used. It also provides a breakdown of spending by category and displays recent transactions.]
- **Feature 2: Expense Management:** [Allows users to record expenses by entering the date, amount, vendor, reference number, category, and additional notes. Users can also upload receipt images and review or delete existing transactions.]
- **Feature 3: Department-Based Expense Tracking:** [Organizes expenses into categories such as Travel, Mechanical, Electrical, Media, and Operations. Users can filter transactions by category, date range, and minimum or maximum expense amount.]
- **Feature 4: Excel Financial Reports:** [Generates downloadable Excel reports for daily, monthly, and yearly spending. Reports include transaction details, budget information, total spending, remaining balance, and a separate worksheet summarizing expenses by category.]

Explain how users interact with the application and what results they receive.

## 3. Technologies Used

List technologies **actually used** and explain their purposes. Remove unused examples.

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Flask / Streamlit | Web interface and application framework, if used |
| Pandas / NumPy | Data processing, if used |
| scikit-learn / Hugging Face | Machine learning or AI, if used |
| SQLite / MongoDB | Data storage, if used |
| External APIs | External data or AI services, if used |
| Other libraries | [Purpose] |

## 4. Application Architecture

Insert a labeled diagram showing user input → interface → Python processing (functions/classes) → model, database, API, or external service → output and/or stored results. Identify which components you develop and how data moves.

![Application architecture](docs/architecture.png)

*Replace the image above with your own diagram saved at `docs/architecture.png`, or change the path to your diagram.*

### How the Application Works

1. The user enters or selects information.
2. The interface passes the information to Python.
3. Python functions or classes process the information.
4. The application interacts with the model, database, or API, as applicable.
5. Results are returned and displayed to the user.
6. Data is saved or updated, if applicable.

Modify these steps to match your actual application.

## 5. Project Structure

Replace this example with your **actual** folders and files:

```text
project2/
├── app.py
├── model/
│   └── student_model.joblib
├── notebooks/
│   └── model_training.ipynb
├── data/
│   └── sample_data.csv
├── docs/
│   └── architecture.png
├── requirements.txt
└── README.md
```

Describe the purpose of your important files. Remove files that are not used.

## 6. Installation and Running the Application

Provide instructions so another student or your professor can run the project.

### Step 1: Clone the repository

```bash
git clone [repository-url]
cd [repository-folder]
```

### Step 2: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run the application

For Streamlit:

```bash
streamlit run app.py
```

For Flask (if configured to start from `app.py`):

```bash
python app.py
```

Replace these examples with the correct commands for your project. Explain database setup, environment variables, model files, or API configuration if needed. **Never commit passwords, API keys, or other secrets.**

## 7. Testing and Validation

| Test | Expected Result | Actual Result |
|---|---|---|
| Normal user input | Application processes input | [Result] |
| Invalid or missing input | Helpful error message | [Result] |
| Model/database/API interaction | Correct response | [Result] |
| Additional feature | Feature works correctly | [Result] |

Describe known limitations or unresolved problems.

## 8. AI-Assisted Development Disclosure

**AI Tools Used:** [ChatGPT, GitHub Copilot, Claude, etc., or None]

### How AI Was Used

Describe AI assistance with design, coding, debugging, testing, documentation, or other tasks. Be specific.

### Student Contributions

Explain the work you personally completed, including design decisions, code modifications, integration, testing, and debugging.

**Student statement:** I reviewed, tested, and can explain the code and technologies used in my application, including code developed with AI assistance.

## 9. Challenges and Lessons Learned

**Challenge 1:** [Description and solution]

**Challenge 2:** [Description and solution]

What new Python programming skills or technologies did you learn?

## 10. Application Screenshots

Include at least two screenshots with captions:

1. Main application interface
2. Application showing a working feature or result

Add screenshots to a folder such as `docs/` and embed them here, for example:

```markdown
![Main application interface](docs/main-screen.png)
```

## 11. Project Links

**GitHub Repository:** [URL]  
**Deployed Application:** [URL, if applicable]  
**Demonstration Video:** [URL, if applicable]

## 12. Future Improvements

1. [Improvement]
2. [Improvement]

---

### Documentation Timeline

- **Deliverable 1 – November 16:** Complete the project overview, planned features, proposed technologies, preliminary architecture diagram, and planned project structure. These are planning sections and may change as development progresses.
- **Deliverable 2 – November 23:** Update the README to reflect implementation progress and initial testing.
- **Final Deliverable – December 8:** Complete all sections, verify setup instructions, add screenshots, and provide final links.

