# **AI Agent Project**

This project is a user-friendly AI Agent designed to extract specific information from a dataset. It automates the process of reading a CSV file or Google Sheet, performing web searches for each entity, and extracting user-defined information using a Language Model (LLM). The extracted data can be viewed, downloaded, or updated directly in a connected Google Sheet.

---

## **Table of Contents**

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Step-by-Step Workflow](#step-by-step-workflow)
  - [Phase 1: Initial Setup](#phase-1-initial-setup)
  - [Phase 2: File Upload and Google Sheets Integration](#phase-2-file-upload-and-google-sheets-integration)
  - [Phase 3: Dynamic Query Input and Prompt Template](#phase-3-dynamic-query-input-and-prompt-template)
  - [Phase 4: Automated Web Search](#phase-4-automated-web-search)
  - [Phase 5: Information Extraction Using LLM](#phase-5-information-extraction-using-llm)
  - [Phase 6: Display and Store Extracted Information](#phase-6-display-and-store-extracted-information)
- [API Keys and Environment Variables](#api-keys-and-environment-variables)
- [Error Handling](#error-handling)
- [Optional Features](#optional-features)
- [Contributing](#contributing)
- [License](#license)

---

## **Features**

1. **File Upload**:
   - Upload a CSV file or connect to a Google Sheet.
   - Preview the uploaded or imported data.

2. **Dynamic Query Input**:
   - Define a custom query using placeholders (e.g., `{company}`).
   - Dynamically generate queries for each entity in the dataset.

3. **Automated Web Search**:
   - Use APIs like SerpAPI to fetch web search results for each entity.

4. **Information Extraction**:
   - Use OpenAI's GPT API to extract specific information from search results.

5. **Data Display and Download**:
   - View extracted data in a user-friendly table format.
   - Download the results as a CSV file or update a connected Google Sheet.

---

## **Technologies Used**

- **Frontend**: Streamlit
- **Backend**: Python
- **APIs**:
  - OpenAI GPT API
  - Google Sheets API
  - SerpAPI (or other search APIs)
- **Libraries**:
  - `pandas`: For data manipulation.
  - `google-api-python-client`: For Google Sheets integration.
  - `streamlit`: For building the dashboard.
  - `openai`: For LLM interaction.
  - `python-dotenv`: For managing environment variables.

---

## **Setup Instructions**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/AI-Agent-Project.git
   cd AI-Agent-Project
