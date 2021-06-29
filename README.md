# data-visualization-iris
Data Visualization on Iris Dataset using pandas, matplotlib, seaborn

Run the commands on Jupyter Notebook

.plot extension from pandas framework is used to make scatterplots

![scatterplot](https://user-images.githubusercontent.com/63820567/123866578-df2ce200-d94a-11eb-9211-222a39f89391.png)

A seaborn jointplot shows bivariate scatterplots and univariate histograms

![seaborn_jointplot](https://user-images.githubusercontent.com/63820567/123866637-f8359300-d94a-11eb-8f52-9e6c8eb667de.png)

Seaborn's FacetGrid is used to color the scatterplot by species

![seaborn_facetgrid](https://user-images.githubusercontent.com/63820567/123866666-01befb00-d94b-11eb-889a-33d02fd00393.png)

Boxplots are used to examine the individual feature in seaborn. 

![seaborn_boxplot](https://user-images.githubusercontent.com/63820567/123866698-0c799000-d94b-11eb-98ab-6ea900025c7c.png)

One way to extend this plot is by adding a layer of individual points on top of it through Seaborn's striplot. We'll use jitter=True so that all the points don't fall in single vertical lines above the species

![seaborn_stripplot](https://user-images.githubusercontent.com/63820567/123866763-1d2a0600-d94b-11eb-97a9-67a479a0c038.png)

A violin plot combines the benefits of the previous two plots and simplifies them denser regions of the data are fatter, and sparser thiner in a violin plot

![seaborn_violinplot](https://user-images.githubusercontent.com/63820567/123866783-24e9aa80-d94b-11eb-8f3a-9ac0ff4e3239.png)

A final seaborn plot useful for looking at univariate relations is the kdeplot, which creates and visualizes a kernel density estimate of the underlying feature
Another useful seaborn plot is the pairplot, which shows the bivariate relation between each pair of features. From the pairplot, we'll see that the Iris-setosa species is separataed from the other two across all feature combinations

![seaborn_pairplot](https://user-images.githubusercontent.com/63820567/123866822-316e0300-d94b-11eb-93d7-a92adcb736a5.png)

The diagonal elements in a pairplot show the histogram by default. We can update these elements to show other things, such as a kde.

![image](https://user-images.githubusercontent.com/63820567/123867085-86aa1480-d94b-11eb-81e6-7f5f84b6f009.png)

Boxplot with Pandas

![image](https://user-images.githubusercontent.com/63820567/123867054-7d20ac80-d94b-11eb-949d-bf42b340ab1b.png)

One cool more sophisticated technique pandas has available is called Andrews Curves. Andrews Curves involve using attributes of samples as coefficients for Fourier series and then plotting these

![image](https://user-images.githubusercontent.com/63820567/123867226-b6591c80-d94b-11eb-9dd1-dfe79793efc1.png)

Another multivariate visualization technique pandas has is parallel_coordinates. Parallel coordinates plots each feature on a separate column & then draws lines connecting the features for each data sample

![image](https://user-images.githubusercontent.com/63820567/123867330-d688db80-d94b-11eb-9335-2ec1e338344f.png)

A final multivariate visualization technique pandas has is radviz which puts each feature as a point on a 2D plane, and then simulates having each sample attached to those points through a spring weighted by the relative value for that feature

![image](https://user-images.githubusercontent.com/63820567/123867463-046e2000-d94c-11eb-85ef-9f3ff8b565e1.png)








