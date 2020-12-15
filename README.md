# integrate
aa


from sympy import *
import math
from sympy.plotting import plot

x = Symbol('x')
y = Symbol('y')

p=math.sqrt(2*math.pi)
q=1/p

h=q*exp(-(x*x)/2)

# 
i=q*exp(-y*y/2)



g = integrate(h,(x,-oo,y))



gg=g**79
ggi=gg*i

# ggyi=y*ggi*80


#plot(ggyi,(y,0,5))




e=integrate(ggyi,(y,0,5))
