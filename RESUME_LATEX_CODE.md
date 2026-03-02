# Data Analyst / SQL Developer Resume - LaTeX Code

Copy the code below and paste into Overleaf (overleaf.com) or your local LaTeX editor.

```latex
\documentclass[a4paper,10pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}
\usepackage[colorlinks=true, urlcolor=blue, linkcolor=blue]{hyperref}

% Font options
\usepackage[sfdefault]{roboto}
\pagestyle{fancy}
\fancyhf{}
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.2in}
\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{\vspace{-4pt}\scshape\raggedright\large}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Custom commands
\newcommand{\resumeItem}[1]{\item\small{{#1 \vspace{-2pt}}}}
\newcommand{\resumeSubheading}[4]{\vspace{-1pt}\item\begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}\textbf{#1} & #2 \\ \textit{\small#3} & \textit{\small #4} \\ \end{tabular*}\vspace{-5pt}}
\newcommand{\resumeProjectHeading}[2]{\item\begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}\small#1 & #2 \\ \end{tabular*}\vspace{-7pt}}
\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%% RESUME STARTS HERE %%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{document}

%----------HEADING----------
\begin{center}
\textbf{\huge \scshape Rohan Vishwakarma} \\
\vspace{5pt}
\href{mailto:rohanvishwakarma471@gmail.com}{\color{blue}\underline{rohanvishwakarma471@gmail.com}} $|$ 
\href{https://github.com/raisun0405}{\color{blue}\underline{github.com/raisun0405}} $|$ 
\href{https://raisun-cv.netlify.app/}{\color{blue}\underline{raisun-cv.netlify.app}} $|$ 
\small Mumbai, India \\
\vspace{5pt}
\textbf{Data Analyst $|$ SQL Developer $|$ Bioengineering Student}
\end{center}
\vspace{5pt}

%-----------OBJECTIVE-----------
\section{Objective}
Bioengineering student with \textbf{12 professional certifications} in Data Analysis, SQL, and Database Management. 600+ hours of hands-on experience with PostgreSQL, MySQL, and data visualization. Seeking internship opportunities in \textbf{data analysis, SQL development, and database management}. Proven track record through projects like Hospital Readmission Dashboard (ML + SQL) and freeCodeCamp Relational Database certification (300 hours).

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
\resumeSubheading
{MIT ADT University}{Pune, India}
{B.Tech in Bioengineering -- School of Bioengineering Sciences \\& Research}{2023 -- 2027}
\resumeItemListStart
\resumeItem{Current Status: Third Year (Semester VI - Even) $|$ \textbf{CGPA: 7.1}}
\resumeItem{Relevant Coursework: Database Management, Data Structures, Statistics, Bioinformatics}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
\small{\item{
\textbf{Data \\& SQL}{: PostgreSQL, MySQL, SQL (Advanced), Database Design, Data Analysis, Pandas} \\
\textbf{Languages}{: Python (Data Analysis), SQL, JavaScript, Bash} \\
\textbf{Tools \\& Platforms}{: Git, GitHub, Linux Terminal, Jupyter, VS Code} \\
\textbf{Data Visualization}{: Matplotlib, Seaborn, Streamlit, Excel} \\
\textbf{Machine Learning}{: Scikit-learn, Basic ML Models, Data Preprocessing}
}}
\end{itemize}

%-----------CERTIFICATIONS-----------
\section{Certifications (12 Total)}
\resumeSubHeadingListStart
\resumeProjectHeading
{\textbf{Top 5 Highlights:}}{}
\resumeItemListStart
\resumeItem{\textbf{DataCamp Associate Data Analyst} -- Professional certification in data analysis, SQL, Python}
\resumeItem{\textbf{DataCamp Data Scientist Associate} -- Professional certification in ML, data science}
\resumeItem{\textbf{freeCodeCamp Relational Databases (v9)} -- 300-hour certification in SQL, PostgreSQL, Bash}
\resumeItem{\textbf{freeCodeCamp Relational Database V8} -- 300-hour certification in database design}
\resumeItem{\textbf{HackerRank SQL (Advanced)} -- Advanced SQL certification}
\resumeItem{\textbf{Full Portfolio:} \href{https://github.com/raisun0405/certificates-portfolio}{\color{blue}\underline{github.com/raisun0405/certificates-portfolio}}}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Data Projects}
\resumeSubHeadingListStart
\resumeProjectHeading
{\textbf{Hospital Readmission Prediction Dashboard} $|$ \emph{Python, SQL, ML, Streamlit} $|$ \href{https://github.com/raisun0405/hospital-readmission-dashboard}{\color{blue}\underline{GitHub}}}{}
\resumeItemListStart
\resumeItem{Built ML system predicting patient readmission risk using 100K+ patient records; achieved 67.2\\% ROC-AUC}
\resumeItem{Designed PostgreSQL database schema for efficient data storage and retrieval}
\resumeItem{Created interactive Streamlit dashboard for real-time risk visualization and analysis}
\resumeItem{Deployed REST API (Flask) for single and batch predictions}
\resumeItemListEnd

\resumeProjectHeading
{\textbf{Celestial Bodies Database} $|$ \emph{SQL, PostgreSQL, Bash} $|$ \href{https://www.freecodecamp.org/certification/raisun/relational-databases-v9}{\color{blue}\underline{Certification Project}}}{}
\resumeItemListStart
\resumeItem{Built normalized database for 1,000+ celestial bodies with complex relationships}
\resumeItem{Wrote 50+ complex SQL queries including JOINs, aggregations, and subqueries}
\resumeItem{Implemented bash scripts for automated data loading and validation}
\resumeItemListEnd

\resumeProjectHeading
{\textbf{World Cup Database} $|$ \emph{SQL, PostgreSQL} $|$ \href{https://www.freecodecamp.org/certification/raisun/relational-databases-v9}{\color{blue}\underline{Certification Project}}}{}
\resumeItemListStart
\resumeItem{Designed relational database schema for FIFA World Cup data (teams, players, matches)}
\resumeItem{Created complex queries for tournament statistics and performance analysis}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
\resumeSubheading
{Freelance Data Automation}{Remote}
{Data Workflow Automation}{Nov 2025 -- Present}
\resumeItemListStart
\resumeItem{Automated data processing workflows using Google Apps Script and SQL queries}
\resumeItem{Managed PostgreSQL databases for client CRM systems}
\resumeItem{Built automated reporting systems saving clients 10+ hours/week}
\resumeItemListEnd
\resumeSubHeadingListEnd

%-----------ACHIEVEMENTS-----------
\section{Additional Information}
\resumeSubHeadingListStart
\resumeProjectHeading
{\textbf{Quick Links:}}{}
\resumeItemListStart
\resumeItem{\textbf{GitHub:} \href{https://github.com/raisun0405}{\color{blue}\underline{github.com/raisun0405}} -- Data projects and open source contributions}
\resumeItem{\textbf{Credly:} \href{https://www.credly.com/users/rohan-vishwakarma}{\color{blue}\underline{credly.com/users/rohan-vishwakarma}} -- Verified digital badges}
\resumeItem{\textbf{Certifications:} \href{https://github.com/raisun0405/certificates-portfolio}{\color{blue}\underline{github.com/raisun0405/certificates-portfolio}} -- 12 certificates with PDFs}
\resumeItem{\textbf{Hackathon:} Smart India Hackathon 2025 Participant (AgriSenseX Team)}
\resumeItemListEnd
\resumeSubHeadingListEnd

\end{document}
```

---

## How to Use

### Option 1: Overleaf (Easiest)
1. Go to [overleaf.com](https://overleaf.com)
2. Create New Project → Blank Project
3. Paste the code above
4. Click "Recompile" to generate PDF
5. Download PDF

### Option 2: Local LaTeX
1. Save code as `resume.tex`
2. Run: `pdflatex resume.tex`
3. Open generated `resume.pdf`

---

## Key Highlights of This Resume

| Feature | Why It Works |
|---------|--------------|
| **"12 Certifications"** in Objective | Quantifies expertise immediately |
| **600+ hours SQL** | Shows depth, not just surface knowledge |
| **Hospital Dashboard** | Real project with 100K records |
| **Top 5 Certs Section** | Recruiters see best credentials first |
| **Certification Projects** | freeCodeCamp projects = hands-on proof |

**Good luck with your internship applications!** 🚀
