# AI ATS (Applicant Tracking System) Resume Analyzer
![Screenshot 2025-04-24 171613](https://github.com/user-attachments/assets/0ca914ed-47aa-4648-a15d-6991e4e5d964)



## Overview

This project is an AI-powered Applicant Tracking System (ATS) resume analyzer built with Streamlit. It helps job applicants understand how well their resume matches a specific job description by providing:
- Percentage match score
- Missing keywords analysis
- Skills gap identification
- Resume improvement suggestions

## Features

- **Resume Analysis**: Upload your PDF resume and get instant feedback
- **Job Description Matching**: See how well your skills align with the job requirements
- **Keyword Identification**: Discover which important keywords are missing from your resume
- **Improvement Suggestions**: Get actionable advice to improve your resume's ATS performance
- **Percentage Match Score**: Quantifiable metric showing your resume's relevance to the position

![Screenshot 2025-04-24 172014](https://github.com/user-attachments/assets/a735120b-99a3-4f62-89ad-8747509f6bea)
![Screenshot 2025-04-24 172056](https://github.com/user-attachments/assets/5f49a854-817d-4ac0-83dd-714e6185abf0)


## How It Works

1. Upload your resume in PDF format
2. The system analyzes your resume content
3. Compares it against the job description
4. Generates a detailed report with:
   - Match percentage
   - Missing keywords
   - Skills gaps
   - Improvement suggestions

![Screenshot 2025-04-24 171613](https://github.com/user-attachments/assets/75e3ffec-294a-43e4-926a-4f97453d73f6)


## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/repository-name
   cd ai-ats-resume-analyzer
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your browser to `http://localhost:8501`

3. Upload your resume PDF and view the analysis results

## Technologies Used

- Python
- Streamlit (for web interface)
- NLP libraries (for text processing)
- PDF parsing libraries
- Machine learning for matching algorithm

## Future Enhancements

- Support for more file formats (DOCX, TXT)
- Integration with LinkedIn profiles
- Multi-job comparison feature
- Enhanced visualization of match results
- Industry-specific analysis templates
