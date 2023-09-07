# Introduction:
- This is a box plot visual using measures as inputs for big data.
- Power BI visuals can only get up to 30,000 data points. It is not possible to use other available box and whisker chart visuals on the AppSource to visualize more than 30,000 data points.
- Therefore, we made this custom visual to show the box plot using measures efficiently without issues, not limited by the number of data points.
- The example dataset is taken from [2 million rows of data on homes for sale | Kaggle](https://www.kaggle.com/datasets/msorondo/argentina-venta-de-propiedades).


# Instructions:
1. Calculate first quartile and third quartile using measures, for example:
- q1 = PERCENTILE.EXC([price], 0.25)
- q3 = PERCENTILE.EXC([price], 0.75)
2. For Minimum, median, Maximum, Mean, and Count, it is possible to use either measures or quick measures.
3. Drag/Select/Check the corresponding value in each input.

# Privacy:
- The Power BI visuals do not collect any personal information. 
- It doesn't access external services or resources.
- The visual only receives data from Power BI and renders the plot.
