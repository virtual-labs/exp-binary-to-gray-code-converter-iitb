**Binary Code:** It is weighted code .i.e. it is a code in which weight is assigned to every symbol position in the code word. The positional weights in binary code are shown below:

Binary Code :-----> …..   2<sup>4</sup> &nbsp;   2<sup>3</sup> &nbsp;   2<sup>2</sup> &nbsp;  2<sup>1</sup> &nbsp;  2<sup>0</sup> &nbsp;  2<sup>-1</sup> &nbsp;  2<sup>-2</sup> &nbsp;  2<sup>-3</sup> &nbsp;  2<sup>-4</sup>   …

Decimal ----------> …..  16  &nbsp;  8  &nbsp;  4  &nbsp;  2 &nbsp;    1  &nbsp;  1/2  &nbsp;  1/4   &nbsp;  1/8 &nbsp;  1/16 …

**Gray Code:** It is a non-weighted code i.e. it does not have any specific/fixed weight assigned to each symbol position in the code word. The unique feature of Gray code is that at a time only “one” bit changes In other words, in Gray code every new code differs from the previous in terms of one single bit.

Use of Gray Code: For correct measurement of angular position of shaft.

 

**Design:** The Binary and their equivalent Gray Codes are related as shown in Fig.1

![image_1](images/image1.png)


Fig.1. Logic Diagram showing relation between Binary and Gray Code.

 

 

Let us now prepare the 3 bit- Binary to 3 bit Gray code truth table:

 
![table_1](images/image018.png)
 
	

From the truth table it is observed that the output G2 is HIGH for minterms m4, m5, m6 and m7. Hence equation defining G2 output can be written as: G2 = Σ m (4, 5, 6, 7). The output G1 is HIGH for minterms m2 and m3 m4 & m5. Hence equation defining G1 output can be written as: G1 = Σ m (2, 3, 4, 5). The output G0 is HIGH for minterms  m1, m2  m5 m6. Hence equation defining G1 output can be written as: G0 = Σ m (1, 2, 5, 6). The Gray outputs for given 3 bit Binary are summarized as follows:

G2 = Σ m (4, 5, 6, 7)

G1 = Σ m (2, 3, 4, 5)

G0 = Σ m (1, 2, 5, 6)

The above Boolean expressions can be implemented using IC 74LS138 as a 3:8 decoder by just connecting its relevant outputs to  4- input NAND gates as shown in Fig. 1.Four input IC74LS20 is used to produce the final Gray code equivalent.

 
![image_2](images/image2.png)

Fig. 2. Binary to Gray Code Converter using IC 74LS138

 

The logic diagram, connection diagram and function table for IC 74LS138 are given below:

![image_3](images/image3.png)


Fig.3. Logic Diagram, Connection Diagram & Function Table of IC 74LS138.

 
#### Numerical:

 Formulas:
Inputs => ![image_1](images/image001.png)


Outputs => ![image_2](images/image002.png)

![image_3](images/image003.png)

![image_4](images/image004.png)

![image_5](images/image005.png)

![image_6](images/image006.png)


Ex-Or Operation Table:

![image_7](images/image007.png)

Truth table:

![table_1](images/image019.png)

Examples:

    Input “011”

![image_8](images/image008.png)

![image_9](images/image009.png)

![image_10](images/image010.png)

![image_11](images/image011.png)


    Output = “010”
  
  Input “110”

![image_12](images/image012.png)

![image_13](images/image013.png)

![image_14](images/image014.png)

![image_15](images/image015.png)

    Output = “101”


    Input “111”

![image_16](images/image016.png)

![image_17](images/image013.png)

![image_18](images/image014.png)

![image_19](images/image011.png)

    Output = “100”



 
<script type="text/javascript" id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"> </script>