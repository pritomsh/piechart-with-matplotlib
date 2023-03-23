# Pie Chart with Matplotlib
Pie charts are used to visually represent data that can be divided into categories or segments that make up a whole. They are particularly useful when you want to show the relative size or proportion of each category in the data set.

Topics I Cover :
 - Add labels
 - Add title
 - Customize wedges
 - Custom Color
 - Auto-label slices
 - Swap label and autopct text positions
 - Explode, shade, and rotate slices
 - Make a function for showing



## Explode, shade, and rotate slices🎉
```bash

explode = (0, 0, 0.1, 0)  # only "explode" the Electronic check
plt.pie(values, labels=labels, 
        explode=explode,
        labeldistance=1.15, 
        wedgeprops = { 'linewidth' : 1, 'edgecolor' : 'white' }, 
        autopct='%1.1f%%',
        shadow=True, startangle=45)

```
![](https://github.com/pritomsh/piechart-with-matplotlib/blob/master/images/explode.png)

