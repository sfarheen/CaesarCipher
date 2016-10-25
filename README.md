Caesar cipher decipherment:

Dicpher the string:
JHLZHYJPWOLYPZVULVMAOLJSHZZPJHSJYFWAVZFZALTZ

Step 1:
Compute the frequency of each letter:
F(J) = 5/44 = 0.1136
F(H) = 4/44 = 0.0909
F(I) = 5/44 = 0.1136
F(Z) = 7/44 = 0.1590
F(Y) = 3/44 = 0.0681
F(P) = 3/44 = 0.0681
F(W) = 2/44 = 0.0454
F(O) = 2/44 = 0.0454
F(V) = 3/44 = 0.0681
F(U) = 1/44 = 0.0227
F(M) = 1/44 = 0.0227
F(A) = 3/44 = 0.0681
F(S) = 2/44 = 0.0454
F(F) = 2/44 = 0.0454
F(T) = 1/44 = 0.0227

Step 2:
Calculating the correlation of the frequency of each letter in the cipher text with the character frequencies in English:
Formula used:
?(i) = ?0 = c = 25 f(c)p(c – i)
Where f(c) is the frequency of character c (in cipher text)
P(c) is the frequency of character in English language, taken from Table of correlation which gives a maximum value if the corresponding key translates the cipher text to plain text.

The program yields the corresponding values of ?(i) for each i ranging from 0 to 25.

Output:
run:
sum[0]=0.028615200000000004
sum[1]=0.04339570000000001
sum[2]=0.03199429999999999
sum[3]=0.034907900000000006
sum[4]=0.04137940000000001
sum[5]=0.04771570000000001
sum[6]=0.039697100000000006
sum[7]=0.051207
sum[8]=0.043577500000000005
sum[9]=0.0271142
sum[10]=0.0270404
sum[11]=0.0416665
sum[12]=0.035876000000000005
sum[13]=0.030244899999999998
sum[14]=0.04246550000000002
sum[15]=0.037314599999999996
sum[16]=0.0380672
sum[17]=0.0466223
sum[18]=0.04257720000000001
sum[19]=0.028591
sum[20]=0.04092440000000001
sum[21]=0.059209899999999996
sum[22]=0.045939600000000004
sum[23]=0.029156799999999997
sum[24]=0.0271098
sum[25]=0.030478900000000003

Step 3:
Trying with the most likely value first,

For i=21 we get plain text as 

OMQEMDOUBTQDUEAZQARFTQOXMEEUOMXODKBFAEKEFQYE

For i=7 we get plain text as

CAESARCIPHERISONEOFTHECLASSICALCRYPTOSYSTEMS

Decrypted text:
CAESAR CIPHER IS ONE OF THE CLASSICAL CRYPTOSYSTEMS
