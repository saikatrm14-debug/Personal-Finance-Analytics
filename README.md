# 💰 Bank-Track: Personal Finance Analytics

Bank-Track is a Python-based personal finance analytics toolkit that transforms raw bank statement PDFs into meaningful financial insights. It automates transaction extraction, categorization, investment tracking, and financial visualization, enabling users to better understand their spending habits, investment patterns, and cash flow.

The project is designed to work with password-protected bank statements and provides an end-to-end workflow—from PDF extraction to publication-quality visualizations.

---

# ✨ Features

## 📄 Bank Statement Processing

- Extracts transactions directly from PDF bank statements
- Supports password-protected PDF statements
- Parses multi-page statements automatically
- Cleans and standardizes transaction records
- Exports cleaned transactions to Excel

---

## 🧹 Data Cleaning

- Removes unnecessary symbols and formatting
- Converts currency values into numeric format
- Standardizes dates
- Extracts merchant names from transaction descriptions
- Organizes data into structured tables

---

## 🏷 Transaction Categorization

Automatically categorizes transactions into meaningful groups, including:

- Salary
- Room Rent
- Food
- Daily Spends
- Groceries
- Shopping
- Fuel
- Travel
- Bank Charges
- ATM Charges
- Others

The categorization engine is fully customizable and can easily be extended with additional rules.

---

## 📈 Investment Tracking

Separates investments from regular expenses.

Supported investment categories include:

- Mutual Funds
- Stocks
- ETFs
- Digital Gold
- Insurance
- NPS / PPF

This enables accurate financial reporting by distinguishing wealth creation from everyday spending.

---

# 📊 Financial Analytics

The toolkit automatically generates a variety of financial insights.

### Monthly Income vs Expense

Visual comparison of monthly income and spending.

---

### Monthly Income vs Expense vs Investment

Separates:

- Income
- Regular Expenses
- Investments

Large one-time expenses can optionally be excluded from monthly expense bars and listed separately for improved financial interpretation.

---

### Monthly Category-wise Expense

Pie charts showing the distribution of spending categories for each month.

---

### Total Expense by Category

Summarizes spending across all categories.

---

### Investment Summary

Visualizes investment allocation by investment type.

---

### Top Merchants

Identifies merchants receiving the highest amount of spending.

---

### Spending by Weekday

Analyzes spending behavior throughout the week.

---

### Major Expense Detection

Automatically identifies unusually large transactions and separates them from regular expenses.

---

# 📁 Generated Outputs

Bank-Track automatically exports:

- Cleaned transaction dataset
- Categorized transaction dataset
- Excel reports
- High-resolution figures
- Financial summaries

All visualizations are automatically saved at publication quality.

---

# 📂 Project Structure

```
Bank-Track/
│
├── Bank_Analysis.ipynb
├── README.md
├── requirements.txt
├── LICENSE
│
├── figures/
│
├── outputs/
│
├── sample_data/
│
└── .gitignore
```

---

# 📦 Requirements

- Python 3.10+
- pandas
- numpy
- matplotlib
- pdfplumber
- openpyxl
- python-dotenv
- jupyter

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 🚀 Usage

1. Place your bank statement PDF in the project directory.
2. If the PDF is password protected, store the password in a `.env` file:

```env
PDF_PASSWORD=your_password
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run the notebook sequentially.

The workflow automatically:

- Reads the PDF
- Extracts transactions
- Cleans the data
- Categorizes expenses
- Detects investments
- Generates financial analytics
- Saves figures and reports

---

# 📊 Current Analytics

✔ Transaction Extraction

✔ PDF Parsing

✔ Password Protected PDF Support

✔ Merchant Identification

✔ Expense Categorization

✔ Investment Identification

✔ Room Rent Detection

✔ Daily Spending Detection

✔ Monthly Income Analysis

✔ Expense Analysis

✔ Investment Analysis

✔ Merchant Analysis

✔ Category Analysis

✔ Weekday Spending Analysis

✔ Major Expense Detection

✔ Automatic Figure Saving

✔ Excel Report Generation

---

# 🔮 Planned Features

- Support for multiple banks
- Automatic merchant learning
- Interactive dashboard
- Budget tracking
- Monthly financial score
- Net worth tracking
- Portfolio analytics
- Cash-flow forecasting
- AI-powered financial insights
- Automatic PDF report generation
- Interactive web application
- Year-over-year financial comparison

---

# 📌 Key Design Philosophy

The project separates **regular expenses** from **investments**, enabling more meaningful financial analysis.

Instead of treating investments as ordinary expenses, Bank-Track tracks them independently, allowing users to distinguish between money spent on consumption and money allocated toward long-term wealth creation.

---

# 🤝 Contributions

Contributions, feature requests, and suggestions are welcome.

If you find a bug or have an idea for improving the project, feel free to open an issue or submit a pull request.

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Acknowledgements

Developed as a personal finance analytics project using Python, with a focus on automated bank statement processing, transaction intelligence, and financial visualization.

---

If you find this project useful, consider giving it a ⭐ on GitHub.
