\documentclass{beamer}
\usepackage[utf8]{inputenc}

\title{My \LaTeX{}  Presentation}
\author{Ganji Srivani}
\date{06 August 2022}

\usetheme{AnnArbor}

\begin{document}

\begin{frame}
\titlepage
\end{frame}

\begin{frame}{Introduction}
\centering
\textbf{Name} : Ganji Srivani \\
\textbf{ID No.} : B191432 \\
\textbf{Class :} 021 \\
\textbf{Branch} : CSE \\
\textbf{Semester} : 2 \\
\textbf{College} : RGUKT Basar \\
\end{frame}

\begin{frame}{COURSE DETAILS}
\begin{table}
\caption{This is my First Table}
\begin{tabular}{|l |l |l |}

 \hline
 S.no & Subject & Credits \\
 \hline
 1 & Maths & 4 \\
 \hline
 2 & Physics & 4 \\
 \hline
 3 & BEE & 4 \\
 \hline
 4 & English & 2 \\
 \hline
 
\end{tabular}
\label{table1}
\end{table}
\end{frame}

\begin{frame}{Photo}
    \begin{figure}[h]
    \includegraphics[scale=0.1]
    {me.jpg}
    \caption{Me}
    \end{figure}
\end{frame}

\end{document}
