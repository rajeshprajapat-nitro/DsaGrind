<h2><a href="https://leetcode.com/problems/sum-of-squares-of-special-elements/">2778. Sum of Squares of Special Elements</a></h2>
<img src="https://img.shields.io/badge/Difficulty-Easy-brightgreen" alt="Difficulty: Easy" />
<hr>
<p>You are given a <strong>1-indexed</strong> integer array <code>nums</code> of length <code>n</code>.</p>
<p>An element <code>nums[i]</code> of <code>nums</code> is called <strong>special</strong> if <code>i</code> divides <code>n</code>, i.e. <code>n % i == 0</code>.</p>
<p>Return the <strong>sum of the squares</strong> of all <strong>special</strong> elements of <code>nums</code>.</p>
<hr>
<p><strong class="example">Example 1:</strong></p>
<pre><strong>Input:</strong> nums = [1,2,3,4]
<strong>Output:</strong> 21
<strong>Explanation:</strong> There are exactly 3 special elements in nums: nums[1] since 1 divides 4, nums[2] since 2 divides 4, and nums[4] since 4 divides 4.
Hence, the sum of the squares is 1 * 1 + 2 * 2 + 4 * 4 = 21.</pre>
<p><strong class="example">Example 2:</strong></p>
<pre><strong>Input:</strong> nums = [2,7,1,19,18,3]
<strong>Output:</strong> 63
<strong>Explanation:</strong> There are exactly 4 special elements: nums[1], nums[2], nums[3], and nums[6], since their indices divide 6.
Hence, the sum of the squares is 2 * 2 + 7 * 7 + 1 * 1 + 3 * 3 = 63.</pre>
<hr>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= nums.length == n &lt;= 50</code></li>
<li><code>1 &lt;= nums[i] &lt;= 50</code></li>
</ul>
