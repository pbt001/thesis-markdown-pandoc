# The Paper

 **Chia Huei Tan**^1,2^ and Patrick Meraldi^1,2^

\small ^1^ Institute of Biochemistry, ETH Zurich, CH-8093 Zurich, Switzerland
\newline
\small ^2^ Department of Physiology and Metabolism, Medical Faculty, University of Geneva, CH-1211 Geneva 4, Switzerland 
\newline   



\pagebreak
 
## Abstract
write your abstract here. LaTeX commands can be used like above to start a new page

## Introduction  
Introduction goes here

## Results

 you can insert nice tables with footnotes using the package _threeparttable_. Use LaTeX language for symbols like \% and \textgreater.
 
\begin{threeparttable}[b]
\captionsetup{font={normalsize,sf}}
\caption{caption}
\begin{tabular}{l c x{2.5cm}}
\toprule
Column 1 & Column 2 & Column 3\\
\midrule
A & B & C \\
D & E & F \\ 
\bottomrule
\begin{tablenotes}
	\item footnote goes here
\end{tablenotes}
\end{table}
 
  
### Second result

I had to insert figures that took up the entire page (like in journal publications), but wanted figure legends to always be on the page facing the figure. For this I used the package _fltpage_. Sadly, development of this package has stopped and it still doesn't work really perfectly. But it worked well enough for me. One bug I ran into was that if you specify the option twoside in your documentclass, fltpage might fail. As I was already using the documentclass **book**, two side is by default, and I did not have to specify it further. Since you are using LaTeX code here, you might need to use LaTeX language for symbols like \% and \textgreater.

\begin{FPfigure}
\centering 
\includegraphics{figures/FigureX.pdf}
\caption{\textbf{This figure is about X} (A) First subfigure. (B) Second subfigure. And sometimes a super long figure legend: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.}
\end{FPfigure}

### Third result 
In case you do call an FPfigure earlier, you will not be able to use markdown's standard figure insert method further down, but need to use LaTeX.

\begin{figure}[h!]
\centering
\includegraphics{figures/FigureY.pdf}
\caption{\textbf{This figure is about Y} (A) First subfigure. (B) Second subfigure.}
\end{figure} 

## Discussion
Write your discussion here.

## Methods
### Cell culture, siRNA and drug treatments

### Immunofluorescence

### Live-cell imaging 

### Statistical Methods

## Acknowledgements

vfill command will ensure that if your text is too short and doesn't fill up the entire page, it won't get spread out till the bottom. 
 
\vfill

\pagebreak
  
In case you want to have separate references, as in my case, I copied over the text from my submitted manuscript and i did not want to rewrite all the citations!
  
## References






6. Li, X. & Nicklas, R. B. Mitotic forces control a cell-cycle checkpoint. Nature 373, 630–632 (1995).

7.  Kiyomitsu, T. & Cheeseman, I. M. Chromosome- and spindle-pole-derived signals generate an intrinsic code for spindle position and orientation. Nat Cell Biol 14, 311–317 (2012).

8. Kiyomitsu, T. & Cheeseman, I. M. Cortical Dynein and asymmetric membrane elongation coordinately position the spindle in anaphase. Cell 154, 391–402 (2013).

9.	Collins, E. S., Balchand, S. K., Faraci, J. L., Wadsworth, P. & Lee, W.-L. Cell cycle-regulated cortical dynein/dynactin promotes symmetric cell division by differential pole motion in anaphase. Mol Biol Cell 23, 3380–3390 (2012).




































