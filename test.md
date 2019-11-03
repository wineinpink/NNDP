$$
\begin{align}
\frac{\partial L}{\partial W}
&= X^T\delta^2 \\
&= \left[\begin{matrix}
 x_1\\x_2
 \end{matrix}\right]
 \left[\begin{matrix}
 -v_1\left(\frac{y_i}{\hat y_i}-\frac{1-y_i}{1-\hat y_i}\right) \cdot\sigma(z^3_1)\cdot(1-\sigma(z^3_1))ReLU'(z^2_1)\\
  -v_2\left(\frac{y_i}{\hat y_i}-\frac{1-y_i}{1-\hat y_i}\right) \cdot\sigma(z^3_1)\cdot(1-\sigma(z^3_1))ReLU'(z^2_2)\\
   -v_3\left(\frac{y_i}{\hat y_i}-\frac{1-y_i}{1-\hat y_i}\right) \cdot\sigma(z^3_1)\cdot(1-\sigma(z^3_1))ReLU'(z^2_3)
 \end{matrix}\right]^T\\
 \end{align}
$$
