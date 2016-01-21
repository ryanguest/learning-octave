# learning-octave
Examples from learning the Octave programming language
 
 
 
~~~
v = [0:.1:2]
plot(v, exp(v),'o')
~~~



Run your own command:

~~~
system('pwd');
/home/rguest/
~~~



Create an n-by-n magic square.

A magic square is an arrangement of the integers 1:n^2 such that the row sums, column sums, and diagonal sums are all equal to the same value.

~~~
magic(3)

ans =

   8   1   6
   3   5   7
   4   9   2

~~~
