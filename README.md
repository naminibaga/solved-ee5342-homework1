Download Link: https://assignmentchef.com/product/solved-ee5342-homework1
<br>
For this problem the observation <em>Y </em>= (<em>Y</em><sub>1</sub><em>,Y</em><sub>2</sub>) is a vector of two random variables <em>Y</em><sub>1</sub><em>,Y</em><sub>2</sub>. The hypotheses are as follows

<em>H</em><sub>0 </sub>: <em>Y</em><sub>1 </sub>∼ N(3<em>,</em>1)<em>,Y</em><sub>2 </sub>∼ N(−1<em>,</em>1) <em>H</em><sub>1 </sub>: <em>Y</em><sub>1</sub><em>,Y</em><sub>2 </sub>∼ <em>P<sub>x</sub>,</em>

where N(<em>µ,σ</em><sup>2</sup>) is the Gaussian distribution with mean <em>µ </em>and variance <em>σ</em><sup>2</sup>, and <em>P<sub>x </sub></em>is the distribution with the following probability density function

<em>, </em>for all <em>x </em>∈ R<em>.</em>

In both the hypotheses, the random variables <em>Y</em><sub>1 </sub>and <em>Y</em><sub>2 </sub>are independent of each other. Use uniform cost, i.e., <em>C</em><sub>00 </sub>= <em>C</em><sub>11 </sub>= 0, <em>C</em><sub>10 </sub>= <em>C</em><sub>01 </sub>= 1.

You must use Monte Carlo simulation to find and plot <em>V </em>(<em>π</em><sub>0</sub>) versus <em>π</em><sub>0</sub>, for <em>π</em><sub>0 </sub>= 0<em>.</em>1<em>,</em>0<em>.</em>2<em>,…,</em>0<em>.</em>9.

<strong>Simulation Details:</strong>

<ul>

 <li>For each value <em>π</em><sub>0</sub>, you must generate 10<sup>6 </sup>instances of <em>Y </em>and apply the Bayes decision rule to perform detection. Use the average cost of these 10<sup>6 </sup>instances as your estimate for <em>V </em>(<em>π</em><sub>0</sub>).</li>

 <li>In each instance, you must randomly generate <em>Y </em>according to either <em>H</em><sub>0 </sub>(with probability <em>π</em><sub>0</sub>) or <em>H</em><sub>1 </sub>(with probability 1 − <em>π</em><sub>0</sub>).</li>

 <li>Ensure that the observation vectors generated for <em>H</em><sub>0 </sub>and <em>H</em><sub>1 </sub>indeed satisfy the probability distributions described above.</li>

 <li>Reference value: at <em>π</em><sub>0 </sub>= 0<em>.</em>25, <em>V </em>≈ 0<em>.</em></li>

</ul>