<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/divisor-game "Divisor Game")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/longest-arithmetic-sequence "Longest Arithmetic Sequence")

## 5030. Maximum Difference Between Node and Ancestor (Medium)

<p>Given the <code>root</code> of a binary tree, find the maximum value <code>V</code> for which there exists different nodes <code>A</code> and <code>B</code> where <code>V = |A.val - B.val|</code> and <code>A</code> is an ancestor of <code>B</code>.</p>

<p>(A node A is an ancestor of B if either: any child of A is equal to B, or any child of A is an ancestor of B.)</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<p><img alt="" src="http://i68.tinypic.com/2whqcep.jpg" style="height: 230px; width: 300px;" /></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[8,3,10,1,6,null,14,null,null,4,7,13]</span>
<strong>Output: </strong><span id="example-output-1">7</span>
<strong>Explanation: </strong>
We have various ancestor-node differences, some of which are given below :
|8 - 3| = 5
|3 - 7| = 4
|8 - 1| = 7
|10 - 13| = 3
Among all possible differences, the maximum value of 7 is obtained by |8 - 1| = 7.
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li>The number of nodes in the tree is between <code>2</code> and <code>5000</code>.</li>
	<li>Each node will have value between <code>0</code> and <code>100000</code>.</li>
</ol>

### Related Topics
  [[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[Depth-first Search](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
For each subtree, find the minimum value and maximum value of its descendants.
</details>