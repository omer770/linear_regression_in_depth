# linear_regression_in_depth
Theory and Practical
![1 B0nXzGa9SCCphwcbQkKs_w](https://user-images.githubusercontent.com/27857345/186633221-0d9923d7-d615-4657-bb17-eef1e1d3d93b.jpeg)
Let the equation of this imaginary line be like this.
![1 9Vqabduj___Vh0jBLQIm5A](https://user-images.githubusercontent.com/27857345/186633436-b3bca1da-9e19-4f87-86f5-77e672586e88.png)

What we have to do is find the coefficients α and β.

If we say the distance from a point to the line,
![1 MQ3_m8ipCLdFJo8rVoE_Tg](https://user-images.githubusercontent.com/27857345/186633465-d3c0de20-65b9-4232-ae9c-4c35394b59e9.png)

Then, if the coefficients α and β are,![1 T6UDJKslos2HDtW7Pvqhwg](https://user-images.githubusercontent.com/27857345/186633501-88249665-8d09-4917-9228-d7badcb27fce.png)


Here we see the equations we have obtained as a result of partial differentiation.
These equations give us the set of normal equations.
![1 nRgfCOM4LED4sb6U5ds34A](https://user-images.githubusercontent.com/27857345/186633655-8e5bb7ee-2397-4320-a2bf-fa2ebe9f8261.png)


If we solve this set of equations using the determinant and elimination method, the value of β will be,
![1 LdPXTG3kPKSoEehZ0ihu0g](https://user-images.githubusercontent.com/27857345/186633700-504cd3e3-56ff-492e-bf32-ff8d1f234551.png)

Then, by solving α from the first of the two normal equations, we find the value of α as follows.
![1 LdPXTG3kPKSoEehZ0ihu0g](https://user-images.githubusercontent.com/27857345/186633733-ad488dbe-f292-4c70-8576-56a6e6059356.png)

If we want to write more simply,
![1 wLRVqjA20pfTPijVkdpoAw](https://user-images.githubusercontent.com/27857345/186633804-77675354-f7cb-43e3-9891-972507d92651.png)

Now let’s rearrange β’s equation using some math magic.
![1 wLRVqjA20pfTPijVkdpoAw](https://user-images.githubusercontent.com/27857345/186633859-8ccc4905-febc-4803-bc18-836a2ddfee5b.png)


Now we can write;

Theorem : Sample data {(𝑥𝑖 , 𝑦𝑖 ); If ; 𝑖 = 1, 2, 3, ⋯ , 𝑛} then 𝑦 = 𝛼 + 𝛽x
![1 v6QhCRm1yaRKmEVcymQYuQ](https://user-images.githubusercontent.com/27857345/186633922-0d0297e0-3ea1-4bfa-a01c-fd6199f9d038.png)
