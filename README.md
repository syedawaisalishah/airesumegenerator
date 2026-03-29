# AI Resume Generator

An intelligent ATS-optimized resume generator powered by AI that tailors your resume to specific job descriptions.

## Features

- **ATS Optimization**: Creates resumes that pass Applicant Tracking Systems
- **Job-Specific Tailoring**: Customizes your resume based on target job descriptions
- **Multiple Export Formats**: Download as DOCX, PDF, or TXT
- **Professional Formatting**: Clean, recruiter-friendly layout
- **AI-Powered**: Uses advanced language models to optimize content

## Installation

1. Install required dependencies:
```bash
pip install streamlit langchain-core langchain-groq python-dotenv python-docx reportlab
```

2. Set up your environment variables:
Create a `.env` file with:
```
GROQ_API_KEY=your_groq_api_key_here
```

## Usage

1. Run the application:
```bash
streamlit run resume.py
```

2. Enter your current resume content in the first text area

3. Paste the target job description in the second text area

4. Click "Generate Resume"

5. Download your optimized resume in your preferred format (DOCX, PDF, or TXT)

## How It Works

The AI Resume Generator:
1. Analyzes your current resume
2. Extracts key requirements from the job description
3. Optimizes your resume content for ATS compatibility
4. Maintains truthfulness while highlighting relevant skills
5. Formats the output professionally

## Resume Sections

The generated resume includes:
- Professional Summary
- Core Skills
- Professional Experience
- Projects
- Education
- Certifications
- Additional Information

## Tips for Best Results

- Provide complete resume information including dates and details
- Include the full job description for better matching
- Review and customize the generated resume before submission
- Keep your original achievements and experiences accurate

## Requirements

- Python 3.8+
- Groq API key
- Internet connection

## License

MIT License
