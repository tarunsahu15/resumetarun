# resumetarun
\documentclass[a4paper,12pt]{article}
\usepackage{latexsym}
\usepackage{xcolor}
\usepackage{float}
\usepackage{ragged2e}
\usepackage[empty]{fullpage}
\usepackage{wrapfig}
\usepackage{lipsum}
\usepackage{tabularx}
\usepackage{titlesec}
\usepackage{geometry}
\usepackage{marvosym}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\usepackage{cfr-lm}
\usepackage[T1]{fontenc}
\setlength{\multicolsep}{0pt} 
\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}
\geometry{left=1.4cm, top=0.8cm, right=1.2cm, bottom=1cm}
% Adjust margins
%\addtolength{\oddsidemargin}{-0.5in}
%\addtolength{\evensidemargin}{-0.5in}
%\addtolength{\textwidth}{1in}
\usepackage[most]{tcolorbox}
\tcbset{
	frame code={}
	center title,
	left=0pt,
	right=0pt,
	top=0pt,
	bottom=0pt,
	colback=gray!20,
	colframe=white,
	width=\dimexpr\textwidth\relax,
	enlarge left by=-2mm,
	boxsep=4pt,
	arc=0pt,outer arc=0pt,
}

\vspace{41mm}
\urlstyle{same}

\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-7pt}]

%-------------------------
% Custom commands
\newcommand{\resumeItem}[2]{
  \item{
    \textbf{#1}{\hspace{0.5mm}#2 \vspace{-0.5mm}}
  }
}

\newcommand{\resumePOR}[3]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1}\hspace{0.3mm}#2 & \textit{\small{#3}} 
    \end{tabular*}
    \vspace{-2mm}
}

\newcommand{\resumeSubheading}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#4}} \\
        \textit{\footnotesize{#3}} &  \footnotesize{#2}\\
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeProject}[4]{
\vspace{0.5mm}\item
    \begin{tabular*}{0.98\textwidth}[t]{l@{\extracolsep{\fill}}r}
        \textbf{#1} & \textit{\footnotesize{#3}} \\
        \footnotesize{\textit{#2}} & \footnotesize{#4}
    \end{tabular*}
    \vspace{-2.4mm}
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

% \renewcommand{\labelitemii}{$\circ$}
\renewcommand{\labelitemi}{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=*,labelsep=1mm]}
\newcommand{\resumeHeadingSkillStart}{\begin{itemize}[leftmargin=*,itemsep=1.7mm, rightmargin=2ex]}
\newcommand{\resumeItemListStart}{\begin{justify}\begin{itemize}[leftmargin=3ex, rightmargin=2ex, noitemsep,labelsep=1.2mm,itemsep=0mm]\small}

\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{2mm}}
\newcommand{\resumeHeadingSkillEnd}{\end{itemize}\vspace{-2mm}}
\newcommand{\resumeItemListEnd}{\end{itemize}\end{justify}\vspace{-2mm}}
\newcommand{\cvsection}[1]{%
\vspace{2mm}
\begin{tcolorbox}
    \textbf{\large #1}
\end{tcolorbox}
    \vspace{-4mm}
}

\newcolumntype{L}{>{\raggedright\arraybackslash}X}%
\newcolumntype{R}{>{\raggedleft\arraybackslash}X}%
\newcolumntype{C}{>{\centering\arraybackslash}X}%
%---- End of Packages and Functions ------

%-------------------------------------------
%%%%%%  CV STARTS HERE  %%%%%%%%%%%
%%%%%% DEFINE ELEMENTS HERE %%%%%%%
\newcommand{\name}{TARUN SAHU} % Your Name
\newcommand{\course}{Bachelor of Technology} % Your Program
\newcommand{\roll}{22U03062} % Your Roll No.
\newcommand{\phone}{8305917052} % Your Phone Number
\newcommand{\emaila}{sahutarun9753162520@gmail.com} %Email 1
% \newcommand{\emailb}{201113057@manit.ac.in} %Email 2




\begin{document}
\fontfamily{cmr}\selectfont
%----------HEADING-----------------


\parbox{\dimexpr\linewidth-2.8cm\relax}{
\begin{tabularx}{\linewidth}{L r} \\
  \textbf{\Large \name} & {\raisebox{0.0\height}{\footnotesize \faPhone}\ +91-\phone}\\
  {Sch. No.: \roll} & \href{mailto:\emaila}{\raisebox{0.0\height}{\footnotesize \faEnvelope}\ {\emaila}} \\
  \course &  \href{mailto:\emailb}{\raisebox{0.0\height}{\footnotesize }\ {}}\\
  {Information Technology} &  \href{https://github.com/tarunsahu15}{\raisebox{0.0\height}{\footnotesize \faGithub}\ {\color{blue}GitHub Profile}} \\
  {Indian Institute Of Information Technology, Bhopal} & \href{https://www.linkedin.com/in/tarun-sahu-27b3a0258}{\raisebox{0.0\height}{\footnotesize \faLinkedin}\ {\color{blue}LinkedIn Profile}}
\end{tabularx}
}
% \parbox{3.0cm}{%
% \flushright \includegraphics[width=2cm,clip]{nitp_logo.png}
% }

\resumeSubHeadingListStart
    \resumeSubheading
      { Indian Institute of Information Technology, Bhopal, India}{CGPA/Percentage: 8.59}
      {B. Tech. - Information Technology}{2026}
    \resumeSubheading
      { Fr Agnel Co-Ed Senior Secondary  School, Bhopal}{CGPA/Percentage: 89.20}
      {CBSE - 10th}{2020}
    \resumeSubheading
      {Magadham International School , Vidisha }{CGPA/Percentage: 92.80}
      {CBSE - 10+2th }{2022}
  \resumeSubHeadingListEnd
\vspace{-3mm}
%



%-----------EXPERIENCE-----------------
% \section{\textbf{Experience}}
%   \resumeSubHeadingListStart
%     \resumeSubheading
%       { DoubtNut Technologies Private Limited}{Work From Home}
%       {Content Developer Intern}{1 April - 1 July, 2021}
%       \vspace{-2.0mm}
%       \resumeItemListStart
%     \item {Contributed as a Content Developer Intern at DoubtNut, specializing in English and Mathematics content.}
%     \item {Played an integral role in enhancing the educational experience for learners, contributing to DoubtNut's commitment to delivering impactful and user-friendly learning resources.}
%     \resumeItemListEnd
      
%   \resumeSubHeadingListEnd
% \vspace{-8.5mm}
%

%-----------Technical skills-----------------
\section{\textbf{Technical Skills and Interests}}
 \begin{itemize}[leftmargin=0.05in, label={}, itemsep=10pt]
    \small{\item{
     \textbf{Languages}{: C/C++, JavaScript } \\
     \vspace{4pt}
     \textbf{Web Dev}{: HTML, CSS, Tailwind} \\
     \vspace{4pt}
     \textbf{Tech Skills}{: DSA, OOPs, DBMS, SQL} \\
     \vspace{4pt}
     % \textbf{Cloud/Databases}{: DBMS} \\
     \textbf{Soft Skills}{: Teamwork, Leadership, Communication skills, Time Management, Problem-solving, Flexibility} \\
     \vspace{4pt}
     % \textbf{Coursework}{: Adobe PhotoShop, Data structure and Algorithms} \\
     \textbf{Areas of Interest}{: Coding, Reading Books, Spirituality, Badminton} \\
    }}
 \end{itemize}
 \vspace{-10pt}


%-----------PROJECTS-----------------
\section{\textbf{Personal Projects}}
\resumeSubHeadingListStart

    \resumeProject
      { \href{https://tarunsahu15.github.io/countdown-counter/}{{\color{blue}Countdown Timer:}{ Display quotes dynamically}}} %Project Name
      { Made Countdown Timer using Front-end Web Development} %Project Name, Location Name
      {Feb, 2024} %Event Dates

      \resumeItemListStart
        \item {Tools \& technologies used: HTML, CSS, JavaScript}
        \item {Developed and implemented a feature that calculates and displays countdown time in days, hours, minutes, and seconds based on user-provided future date; Integrated an API to retrieve and dynamically display new quotes every 30 seconds.}
        
    \resumeItemListEnd
    \vspace{-4mm}

%     \resumeProject
%       { \href{https://anurag575sharma.github.io/Weather_App/}{{\color{blue}Weather App:} {Fetch Weather Dynamically}} } %Project Name
%       { Can see weather of your current Location as well as other city } %Project Name, Location Name
%       {June, 2024} %Event Dates

%       \resumeItemListStart
%         \item {Tools \& technologies used: HTML , CSS , JavaScript }
%         \item { User can grant location and can also fetch any other location's weather.}
%         \item {Built with HTML, CSS, and JavaScript ,
%         uses weather API.}
%     \resumeItemListEnd

%     \resumeProject
%       { \href{https://anurag575sharma.github.io/Todo/}{{\color{blue} Todo App:} {}} } %Project Name
%       { User can add task by using input box and date from callendar. } %Project Name, Location Name
%       {Oct, 2023} %Event Dates

%       \resumeItemListStart
%         \item {Tools \& technologies used: HTML , CSS , JavaScript }
%         \item { We can add our important task and their deadline}
%     \resumeItemListEnd
%     \vspace{-3mm}
    
   
% \vspace{-5.5mm}



%-----------Positions of Responsibility-----------------
% \section{\textbf{Positions of Responsibility}}
% \vspace{-0.4mm}
% \resumePOR{ Student Co-Coordinator, } % Position
%     {Inspire MANIT} %Club,Event
%     {January, 2024 - Present} %Tenure Period
% \resumePOR{ Event Organizer, } % Position
%     {TechSphurti Event in IITK'24} %Club,Event
%     {3-10 January, 2024} %Tenure Period
% \resumePOR{ Executive, } % Position
%     {Avantikulam Education  } %Club,Event
%     {November, 2023 - Present} %Tenure Period
% \vspace{-2mm}


%-----------Achievements-----------------
\section{\textbf{Achievements}}
\vspace{-0.4mm}

\resumePOR { \href{https://leetcode.com/u/tarun15082002/} {\color{blue}{Leet code Profile}}}{  solved over 400+ problems on various platforms like GFG, Leetcode , CodeForces and Coding Ninjas combined. } % Award
    {} % Event
    
 \resumePOR{ \href{https://codeforces.com/profile/sahutarun9753162520} {\color{blue}{Codeforces Profile}}}{Newbie MAX Rating (1093)} %{Upgraded Branch from Electrical Engineering to Computer Science Engineering} % Award
{}

\vspace{-5mm}



%-------------------------------------------
\end{document}
