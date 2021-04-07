- 👋 Hi, I’m @yshca
- 👀 I’m interested in programing.
- 🌱 I’m currently learning DSA.
- LEETCODE QUES.
- https://leetcode.com/problems/k-th-symbol-in-grammar/
- class Solution {
public:
    int kthGrammar(int N, int K) 
    {
     if (N == 1) 
         return 0;
	 if (K % 2 == 0) 
     {
         if(kthGrammar(N - 1, K / 2) == 0)
             return 1;
         else
             return 0;
     }
	 else 
          {
         if(kthGrammar(N - 1, (K + 1) / 2) == 0)
             return 0;
         else
             return 1;
     }
        
    }
};






<!---
yshca/yshca is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
