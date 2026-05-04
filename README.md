# ITPM_Assaignment1- IT23295506
how accurately converts chat-style Singlish input into Sinhala output: 
Singlish automated testing using Playwright

Repository link - https://github.com/yohan317/ITPM_Assaignment1

## Tools & Technologies utilized
- Python
- Playwright
- OpenPyxl

## File structure
- `Assignment 1 - Test cases.xlsx` (Contains test cases)
- `test_automation.py` (Playwright automation script)
- `README.md` (Project documentation)

## A simple guide to run the project

Open terminal inside the project folder.

### Install dependencies
```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

### Run the command
```bash
python3 test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

## Output
Actual result of each scenario with the respective status (Pass/Fail) will be auto-updated into the Excel file (two columns: **Actual output** and **Status**).

## Test case information
- 15 Singlish-to-Sinhala translation test cases covering:
  - Question forms
  - Requests
  - Inputs with punctuation marks
  - Romanization / Spelling Variants
  - Isolated English Word Insertions in Singlish
  - Multi-Word English Phrases in Singlish
  - English Digital Terms in Singlish
  - Platform/App Names in Singlish
  - Inputs with Time Formats
  - Inputs with Slang and Casual Phrasing
