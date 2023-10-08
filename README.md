![](untitled.png)
Beyond-30
=======================
In this repo we will look into the question of what comes before the axiom of Rule 30. 
The idea for this repo went through a number of changes, it started as an attempt to make a compression algorithm based on rule 30, this prooved to be of limited use, but it has lead to an inverse rule for rule 30.

Definitions
=======================
Let $S_i^k$ the $i^{th}$ line and $k^{th}$ position of rule-30 

Invers rule 30
=======================
We can write rule 30 as: 


  $S_i^k=S_{i-1}^{k-1} \oplus [S_i^{k-1} + S_{i+1}^{k-1}]$ 

and it can be reformulated to 

$S_{i-1}^{k-1}= S_i^k\oplus [S_i^{k-1} + S_{i+1}^{k-1}]$ 

this means given any line $S^n$, $S_m^{n-1}$ $S_{m+1}^{n-1}$ with $m$ the length of the line $S^n$