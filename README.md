java c

R Analysis Project [15 marks]Please finish the tasks according to the requirements. All the tasks need to be finished by using R. Present your results in the word file, copy and paste all your R code in the end of this word file, and then submit your word file via the Turnitin link in iLearn.Task: Stock Return and Portfolio AnalysisIn   the file named as “Stock.csv”, you have been provided with the daily prices of three stocks from 2012 to 2018.a.   Pls plot the daily prices of three stocks (either in one figure or three separate figures). Pls include date information and make relevant title and legend.                                                                   [1.5 mark]b.   Calculate the daily   log returns of all the three stocks and express them in percentages.Pls report the descriptive statistics of log returns of three stocks in Table 1. Pls change the names in Table 1 to the stock names in your file. [note: SD stands for standard deviation; and N stands for number of observations]          [1 mark]Table 1: Summary StatisticsVariableStock 1Stock 2Stock 3Min         Max         Mean         Median         SD          Skewness         Kurtosis         N         c.      Pls report the   correlation   matrix of log returns of three stocks in Table 1. Pls change the names in Table 1 to the stock names in your file.          [1 mark]Table 2: Correlation MatrixVariableStock 1Stock 2Stock 3Stock 1         Stock 2         Stock 3         d.   There is a file named as “FF3factors.csv” in your folder. Merge your stock return data with the Fama French three factors data,   which are all in percentages.    Pls create a new variable StockR for all the three stocks, which equals to the difference between daily   log return of each stock and RF (available in the FF3factors.csv), and run a regression of:StockR = α + βMktR + u,where MktR   is the daily market excess return. Report the regression results for all the three stocks in tables (you can use only one table to summarize all the results or use three separate tables). [1.5 mark]e.   Plot the time-varying   betas of these three stocks separately or together. To calculate the time-varying beta, use a 252-day   fixed window.    In the plot, the X-bar should   be the date of the last day in the fixe代 写R Analysis ProjectR
代做程序编程语言d window. For instance, if this window covers from day 1 to day 252, use the date of day 252 to label the beta estimated in this window, and so on so forth.             [1.5 mark]f.   Pls run regressions of :StockR = α +   β1MktR +   β2SMB +   β3HML + u.
                        Report the regression results for all the three stocks in tables (you can use only one table to summarize all the results or three separate tables). [1.5 mark]g.   Pls make your comments by comparing the results in c   and d.      [1 mark].[Hint: which model can fit the data better?]h.   If an investor would like to form. a portfolio with a targeted expected return of 0.05% and achieve the minimized standard deviation by investing in these three stocks in the “Stock.csv” file. If the daily risk free rate is 0.02%, what is the Sharpe ratio of this optimal portfolio, given there is no short sale constraint? [1mark] [hint: can use the library of “quadprog”]i.   If an investor would like to form. a portfolio with a targeted expected return of 0.05% and achieve the minimized standard deviation by investing in these three stocks. If the daily risk free rate is 0.02%, what is the Sharpe ratio of this optimal portfolio, given there is   short sale constraint (i.e., you cannot short sell the stocks)? [1   mark] [hint: can use the library of “quadprog”]j.   By comparing your answer in g) and h), is there any difference in their Sharpe ratios? Why that’s the case? [1 mark]k.   Given there is no short sale constraint, pls draw an efficient frontier that satisfies the following conditions: 1. The range of the mean return of the portfolio is from 0.75*min of the mean return of three stocks to 1.25*max of the mean return of three stocks; 2. Pls create 500 optimal portfolios in this range; 3. Then pls plot all the risk-return combination of the 500 optimal portfolios (i.e., the efficient frontier). [1   mark]l.   Following j, pls draw the Capital Allocation Line that connects the risk-free rate and the Tangency portfolio. What’s the slope of this CAL? [1 mark]m.   An investor invests 30% in the risk free rate and 70% in the tangency portfolio. Calculate the expected return and standard deviation of this complete portfolio.    [1 mark]               

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
