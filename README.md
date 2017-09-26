# Statistical Application Development with R and Python - Second Edition
This is the code repository for [Statistical Application Development with R and Python - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/statistical-application-development-r-and-python-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788621199), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Statistical Analysis involves collecting and examining data to describe the nature of data that needs to be analyzed. It helps you explore the relation of data and build models to make better decisions.

This book explores statistical concepts along with R and Python, which are well integrated from the word go. Almost every concept has an R code going with it which exemplifies the strength of R and applications. The R code and programs have been further strengthened with equivalent Python programs. Thus, you will first understand the data characteristics, descriptive statistics and the exploratory attitude, which will give you firm footing of data analysis. Statistical inference will complete the technical footing of statistical methods. Regression, linear, logistic modeling, and CART, builds the essential toolkit. This will help you complete complex problems in the real world.

You will begin with a brief understanding of the nature of data and end with modern and advanced statistical models like CART. Every step is taken with DATA and R code, and further enhanced by Python.

The data analysis journey begins with exploratory analysis, which is more than simple, descriptive, data summaries. You will then apply linear regression modeling, and end with logistic regression, CART, and spatial statistics.

By the end of this book you will be able to apply your statistical learning in major domains at work or in your projects.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
from scipy.stats import norm
xr = np.arange(-4,4.1,0.1)
fx = norm.pdf(xr)
pylab.plot(xr,fx)
p1 = np.arange(0,4.02,0.02)
pylab.fill_between(p1,norm.pdf(p1))
pylab.show()
xr = np.arange(-4,4.1,0.1)
fx = norm.pdf(xr)
pylab.plot(xr,fx)
p2 = np.arange(-1.96,1.961,0.001)
pylab.fill_between(p2,norm.pdf(p2))
pylab.show()
xr = np.arange(-4,4.1,0.1)
fx = norm.pdf(xr)
pylab.plot(xr,fx)
p3 = np.arange(-2.58,2.581,0.001)
pylab.fill_between(p3,norm.pdf(p3))
pylab.show()
```



## Related Products
* [Mastering RStudio - Develop, Communicate, and Collaborate with R](https://www.packtpub.com/application-development/mastering-rstudio-–-develop-communicate-and-collaborate-r?utm_source=github&utm_medium=repository&utm_campaign=9781783982547)

* [Building Web Applications with Python and Neo4j](https://www.packtpub.com/application-development/building-web-applications-python-and-neo4j?utm_source=github&utm_medium=repository&utm_campaign=9781783983988)

* [Data Mining with Python: Implementing Classification and Regression](https://www.packtpub.com/big-data-and-business-intelligence/data-mining-python-implementing-classification-and-regression?utm_source=github&utm_medium=repository&utm_campaign=9781785885716)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
