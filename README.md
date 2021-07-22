#  PREDICTING THE GROWTH AND TREND OF COVID-19 PANDEMIC USING MACHINE LEARNING

This project is based on the paper https://www.sciencedirect.com/science/article/pii/S254266052030055X that uses the following mathematical model to approximate certain dataset.
$$
f(x)=k \cdot \gamma \cdot \beta \cdot \alpha^{\beta} \cdot x^{-1-\beta} \cdot \exp \left(-\gamma\left(\frac{\alpha}{x}\right)^{\beta}\right)
$$
Here, $f(x)$ denotes the number of cases with $x$, where $x>0$ is the time in number of days from the first case, and $\alpha, \beta, \gamma>0, \in \mathbb{R}$ are parameters of the model. Now, we can find the appropriate values of the parameters $\alpha, \beta$ and $\gamma$ to minimize the error between the predicted cases $(y=f(x))$ and the actual cases $(\hat{y}) .$


Their  prediction model is available online at https://github.com/shreshthtuli/covid-19-prediction. The
dataset used for this work is the Our World Dataset, available at https://github.com/owid/covid-19-data/
tree/master/public/data/. 
