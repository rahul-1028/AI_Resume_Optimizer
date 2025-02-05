Steps to Execute the AI Resume Optimizer Script

1. Install Dependencies
Ensure you have the required Python libraries installed. Run the following command in your terminal:
pip install spacy PyPDF2 scikit-learn matplotlib wordcloud

2. Download the spaCy NLP Model
Since the script uses spaCy for Natural Language Processing, download the English language model:
python -m spacy download en_core_web_sm

3. Place Your Resume PDF in the Same Directory
Save your resume as resume.pdf in the same directory as the script.

4. Run the Python Script
Execute the script in your terminal or command prompt:
python script_name.py
(Replace script_name.py with the actual filename.)

5. Expected Output
Console Output:
List of found keywords in the resume.
List of missing keywords to improve ATS compatibility.
Match percentage with the job description.

Word Cloud Visualization:
A word cloud will be displayed, showing frequently used terms in the resume.
