# BitsWise
CHeck for important questions and notes for this topic.

Imp Takeaways for problem solving -
--> The most significant bit is greater than the whole sum of all the array. proof:  1 1 1 1, in this the first bit is 8 and the sum of all other is 7, 
We can also use gp sum to calculate that and the results ccomes out be the 2^(k) -1 while the most significant bit 2^(k). 
Always think of the above while solving a greedy problem.

--> Each bit can be worked with independtly, most of the time in questions taking numbers are cumbersome but if we will look at the bits we might some idea to go on with.

Alot of bulltin functions are there to help. We can calculate the number of most significant bit by using bulltin count trailing 0 and then - the number of bits to get the ans. int is 32 bit.


IMP _ NOTES - 
lets add two number without using +, then think of the numbers in binary.
We will see all the bits that are common, ie. we will & them.
Will come 2 times and those who are uncommon ie. ^ them will come only once.

Proof -
lets say I have 0 1 0 1 and 1 1 0 1, 
now if I want to write the sum I can simply write it as,  ( 1 + 4 ) + ( 1 + 4 + 8 ), Now easily 
it is observable than 1 and 4 that are common comes twice while the other one comes only one time. 

-----------------
This idea may not be beneficiary to solve the next problem however, the idea of how we approached the proof will be god like for it. Please attempt it.

https://codeforces.com/problemset/problem/1514/B
