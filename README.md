# Adding Shock Events into Gaussian Price Processes
We all know there are discrete events that affect the market. Macro events like recessions, market-driven breaks such as occur from over-leverage, and revaluations in fundamentals (e.g. “irrational exuberance”). Each type has a different signature in terms of how it affects prices. For example, market-driven events tend to drop and recover faster, while macro events tend to move slowly over a long time period.


Historically, these events appear with a particular frequency, and can each be modeled as a Poisson arrival. The result is what is like what is called a compound Poisson process. The difference is that when an event arrives, it is not a one-period shock - its effect persists.


In this project, we will attempt to solve and research the following question:


<b>What happens to the distribution of equity returns when we introduce non- Gaussian large shock events, versus the usual assumption of a Gaussian distribution?</b>
Please see the report https://github.com/shreysamdani/Adding-Shock-Events-into-Gaussian-Price-Processes/blob/main/doc.pdf. For any code / the LaTeX behind the project, please see main.ipynb and doc.Rnw. The Python environment used is specified in the environment.yml file.

<hr>

This project was conducted with the assistance of Richard Bookstaber from Fabric Risk.
