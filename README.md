Download Link: https://assignmentchef.com/product/solved-cs760-homewok-1-background-test
<br>
<h1>Vectors and Matrices</h1>

Consider the matrix <em>X </em>and the vectors <strong>y </strong>and z below:

9                        7

<strong>y </strong>=                     <strong>z </strong>=

8                        6

<ol>

 <li>What is the inner product of the vectors <strong>y </strong>and <strong>z</strong>? (this is also sometimes called the <em>dot product</em>, and is sometimes written as <strong>y </strong><em><sup>T </sup></em><strong>z</strong>)</li>

 <li>What is the product <em>X </em><strong>y </strong>?</li>

 <li>Is <em>X </em>invertible? If so, give the inverse, and if no, explain why not. <em>X </em>is invertible. The inverse matrix is</li>

 <li>What is the rank of <em>X </em>? Rank(<em>X </em>)</li>

</ol>

<h1>2          Calculus</h1>

<ol>

 <li>If <em>y </em>= 4<em>x</em><sup>3 </sup><em>x</em><sup>2 </sup>+ 7 then what is the derivative of <em>y </em>with respect to <em>x</em>?</li>

 <li>, what is the partial derivative of <em>y </em>with respect to <em>x</em>?</li>

</ol>

<h1>3          Probability and Statistics</h1>

Consider a sample of data <em>S </em>= f 0<em>; </em>1<em>; </em>1<em>; </em>0<em>; </em>0<em>; </em>1<em>; </em>1g created by flipping a coin <em>x </em>seven times, where 0 denotes that the coin turned up heads and 1 denotes that it turned up tails.

<ol>

 <li>What is the sample mean for this data?</li>

 <li>What is the sample variance for this data?</li>

 <li>What is the probability of observing this data, assuming it was generated by flipping a biased coin with <em>p</em>(<em>x </em>= 1) = 0<em>:</em>7<em>; p</em>(<em>x </em>= 0) = 0<em>:</em>3.</li>

 <li>Note that the probability of this data sample would be greater if the value of <em>p</em>(<em>x </em>= 1) was not 0<em>:</em>7, but instead some other value. What is the value that maximizes the probability of the sample <em>S </em>? Please justify your answer.</li>

 <li>Consider the following joint probability table where both <em>A </em>and <em>B </em>are binary random variables:</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="34">A</td>

   <td width="24">B</td>

   <td width="55"><em>P </em>(<em>A; B</em>)</td>

  </tr>

  <tr>

   <td width="34">0</td>

   <td width="24">0</td>

   <td width="55">0.1</td>

  </tr>

  <tr>

   <td width="34">0</td>

   <td width="24">1</td>

   <td width="55">0.4</td>

  </tr>

  <tr>

   <td width="34">1</td>

   <td width="24">0</td>

   <td width="55">0.2</td>

  </tr>

  <tr>

   <td width="34">1</td>

   <td width="24">1</td>

   <td width="55">0.3</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>What is <em>P </em>(<em>A </em>= 0<em>; B </em>= 0)?</li>

 <li>What is <em>P </em>(<em>A </em>= 1)?</li>

 <li>What is <em>P </em>(<em>A </em>= 0j<em>B </em>= 1)?</li>

 <li>What is <em>P </em>(<em>A </em>= 0 _ <em>B </em>= 0)?</li>

</ul>

<h1>4          Big-O Notation</h1>

For each pair (<em>f; g</em>) of functions below, list which of the following are true: <em>f </em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)), <em>g</em>(<em>n</em>) = <em>O</em>(<em>f </em>(<em>n</em>)), both, or neither. Briefly justify your answers.

<ol start="2">

 <li><em>f </em>(<em>n</em>) = ln(<em>n</em>), <em>g</em>(<em>n</em>) = log<sub>2</sub>(<em>n</em>).</li>

 <li><em>f </em>(<em>n</em>) = <em>n</em><sup>100</sup>, <em>g</em>(<em>n</em>) = 100<em><sup>n </sup></em>.</li>

</ol>

Medium background Test

<h1>5          Algorithm</h1>

Divide and Conquer: Assume that you are given a sorted array with <em>n </em>integers in the range [ 10<em>; </em>+ 10]. Note that some integer values may appear multiple times in the array. Additionally, you are told that somewhere in the array the integer 0 appears exactly once. Provide an algorithm to locate the 0 which runs in <em>O</em>(log(<em>n</em>)). Explain your algorithm in words, describe why the algorithm is correct, and justify its running time.

<h1>6           Probability and Random Variables [5 pts]</h1>

<h2>6.1         Probability</h2>

State true or false. Here  denotes the sample space and <em>A <sup>c </sup></em>denotes the complement of the event <em>A </em>.

<ol>

 <li>For any <em>A; B </em>, <em>P </em>(<em>A </em>j<em>B </em>)<em>P </em>(<em>B </em>) = <em>P </em>(<em>B </em>j<em>A </em>)<em>P </em>(<em>A </em>).</li>

 <li>For any <em>A; B </em>, <em>P </em>(<em>A </em>[ <em>B </em>) = <em>P </em>(<em>A </em>) + <em>P </em>(<em>B </em>)                <em>P </em>(<em>A </em>j<em>B </em>).</li>

 <li>For any <em>A; B; C </em>such that.</li>

 <li>For any <em>A; B </em>such that <em>P </em>(<em>B </em>) <em>&gt; </em>0<em>; P</em>(<em>A <sup>c</sup></em>) <em>&gt; </em>0, <em>P </em>(<em>B </em>j<em>A <sup>C </sup></em>) + <em>P </em>(<em>B </em>j<em>A </em>) = 1.</li>

 <li>For any <em>n </em>events, then are mutually independent.</li>

</ol>




<h2>6.2         Discrete and Continuous Distributions</h2>

Match the distribution name to its probability density / mass function. Below, j<em>x </em>j = <em>k</em>.

(f) <em>f </em>(<em>x </em>;     (<em>x          </em>)<em><sup>T             </sup></em><sup>1</sup>(<em>x          </em>)

)<em><sup>n         x </sup></em>for <em>x </em>2 f0<em>; : : : ; n</em>g; 0

otherwise

<ul>

 <li>L aplace</li>

 <li>Multinomial  and</li>

 <li>Poisson  otherwise</li>

 <li>Dirichlet  (j) <em>f </em>(<em>x</em>; <em>;</em>) = ( ) <em>x               </em>1<em>e </em><em>x </em>for <em>x </em>2 (0<em>; </em>+ 1 ); 0 oth-</li>

 <li>Gamma  erwise</li>

</ul>

(k) <em>f </em>(<em>x </em>;       ) = and

<sup>P</sup>; 0 otherwise

for all <em>x </em>2 <em>Z </em><sup>+ </sup>; 0 otherwise

<h2>6.3         Mean and Variance</h2>

<ol>

 <li>Consider a random variable which follows a Binomial distribution: <em>X </em>Binomial(<em>n; p</em>).

  <ul>

   <li>What is the mean of the random variable? (</li>

   <li>What is the variance of the random variable?</li>

  </ul></li>

</ol>

<ol start="2">

 <li>L et <em>X </em>be a random variable and E [<em>X </em>] = 1<em>; </em>Var(<em>X </em>) = 1. Compute the following values:

  <ul>

   <li>E [3<em>X </em>]</li>

  </ul></li>

</ol>

<ul>

 <li>Var(3<em>X </em>)</li>

 <li>Var(<em>X </em>+ 3)</li>

</ul>

<h2>6.4         Mutual and Conditional Independence</h2>

<ol>

 <li>If <em>X </em>and <em>Y </em>are independent random variables, show that .</li>

</ol>

<em><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/07/898.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/07/898.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></em>

<ol start="2">

 <li>If <em>X </em>and <em>Y </em>are independent random variables, show that Var(<em>X </em>+ <em>Y </em>) = Var(<em>X </em>) + Var(<em>Y </em>). Hint: Var(<em>X </em>+ <em>Y </em>) = Var(<em>X </em>) + 2Cov(<em>X; Y </em>) + Var(<em>Y </em>)</li>

 <li>If we roll two dice that behave independently of each other, will the result of the first die tell us something about the result of the second die?</li>

</ol>

If, however, the first die’s result is a 1, and someone tells you about a third event — that the sum of the two results is even — then given this information is the result of the second die independent of the first die?

<h2>6.5          Law of Large Numbers and the Central Limit Theorem</h2>

Provide one line justifications.

<ol>

 <li>Suppose we simultaneously flip two independent fair coins (i.e., the probability of heads is 1<em>=</em>2 for each coin) and record the result. After 40,000 repetitions, the number of times the result was two heads is close to 10,000. (Hint: calculate how close.)</li>

 <li>L et <em>X <sub>i </sub></em>N(0<em>; </em>1) and , then the distribution of <em>X </em>satisfies</li>

</ol>

p  <em><sub>       n </sub></em>!    1

<em>nX </em>!         N(0<em>; </em>1)

E[<em>:</em>




<h1>7           Linear algebra</h1>

<h2>7.1         Norm-enclature</h2>

Draw the regions corresponding to vectors <strong>x </strong>2 R <sup>2 </sup>with the following norms:

<ol>

 <li>jj<strong>x </strong>jj<sub>1 </sub>1 (Recall that jj<strong>x </strong>jj<sub>1 </sub>= P <em><sub>i </sub></em>j<em>x <sub>i </sub></em>j)</li>

 <li>jj<strong>x </strong>jj<sub>2 </sub>1 (Recall that</li>

 <li>jj<strong>x </strong>jj<sub>1 </sub>1 (Recall that jj<strong>x </strong>jj<sub>1                       </sub>= max<em><sub>i </sub></em>j<em>x <sub>i </sub></em>j)</li>

 <li>7.2         Geometry</li>

</ol>

Prove that these are true or false. Provide all steps.

<ol>

 <li>The smallest Euclidean distance from the origin to some point <strong>x </strong>in the hyperplane <strong>w</strong>.</li>

 <li>The Euclidean distance between two parallel hyperplane <strong>w </strong><em><sup>T </sup></em><strong>x </strong>+ <em>b</em><sub>1 </sub>= 0 and <strong>w </strong><em><sup>T </sup></em><strong>x </strong>(Hint: you can use the result from the last question to help you prove this one).</li>

</ol>

<h1>8           Programming Skills [5pts]</h1>

Sampling from a distribution. For each question, submit a scatter plot (you will have 5 plots in total). Make sure the axes for all plots have the same limits. (Hint: You can save the figure as a pdf, and then use includegraphics to include the pdf in your latex file. Suggest to use Python or Matlab.)

<ol>

 <li>Draw 100 samples <strong>x </strong>= [<em>x</em><sub>1</sub><em>; x</em><sub>2</sub>]<em><sup>T </sup></em>from a 2-dimensional Gaussian distribution with mean (0<em>; </em>0)<em><sup>T </sup></em>and identity covariance matrix, i.e., , and make a scatter plot (<em>x</em><sub>1 </sub> <em>x</em><sub>2</sub>). For each question below, make each change separately to this distribution.</li>

 <li>Make a scatter plot with a changed mean of (1<em>; </em>1)<em><sup>T </sup></em>.

  <ul>

   <li>0</li>

  </ul></li>

 <li>Make a scatter plot with a changed covariance matrix of .</li>

</ol>

0    2

Solution figure goes here.

<ul>

 <li>0<em>:</em>2</li>

</ul>

<ol start="4">

 <li>Make a scatter plot with a changed covariance matrix of . 0<em>:</em>2 2

  <ul>

   <li>0<em>:</em>2</li>

  </ul></li>

 <li>Make a scatter plot with a changed covariance matrix of . 0<em>:</em>2 2</li>

</ol>