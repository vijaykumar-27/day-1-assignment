# day-1-assignment

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

x =[1,2,3,4,5]
y =[0,2,4,6,8]

plt.plot(x,y,label ='2x') #plottting the line graph

plt.title("My first chart") #Adding the title
plt.xlabel("x axis") #Adding the x labe
plt.ylabel("y axis") #Adding the y label

#Resizing the graph
plt.xticks([0,1,2,3,4]) 
plt.yticks([2,4,6,8.10])

#Save the graph
plt.savefig('myfirstgraph.png')

plt.legend() #Adding legend
plt.show()
