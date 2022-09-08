# training
class Solution {public: int singleNumber(vector&lt;int>&amp; nums) { int mask = 0; for(int i : nums) mask ^= i; return mask; }};
