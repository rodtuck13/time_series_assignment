# Time Series Homework Assignment

## Time Series Analysis:

ARMA Model Results

Dep. Variable:	Settle	No. Observations:	7514

Model:	ARMA(2, 1)	Log Likelihood	-7894.071

Method:	css-mle	S.D. of innovations	0.692

Date:	Tue, 23 Feb 2021	AIC	15798.142

Time:	00:32:14	BIC	15832.765

Sample:	0	HQIC	15810.030

coef	std err	z	P>|z|	[0.025	0.975]

const	0.0063	0.008	0.804	0.422	-0.009	0.022

ar.L1.Settle	-0.3062	1.277	-0.240	0.811	-2.810	2.198

ar.L2.Settle	-0.0019	0.019	-0.099	0.921	-0.040	0.036

ma.L1.Settle	0.2946	1.277	0.231	0.818	-2.209	2.798

Roots

Real	Imaginary	Modulus	Frequency

AR.1	-3.3355	+0.0000j	3.3355	0.5000

AR.2	-157.2070	+0.0000j	157.2070	0.5000

MA.1	-3.3945	+0.0000j	3.3945	0.5000


ARIMA Model Results

Dep. Variable:	D.Settle	No. Observations:	7514

Model:	ARIMA(5, 1, 1)	Log Likelihood	-41944.619

Method:	css-mle	S.D. of innovations	64.281

Date:	Tue, 23 Feb 2021	AIC	83905.238

Time:	00:32:15	BIC	83960.635

Sample:	1	HQIC	83924.259

coef	std err	z	P>|z|	[0.025	0.975]

const	0.3160	0.700	0.451	0.652	-1.056	1.688

ar.L1.D.Settle	0.2822	0.699	0.404	0.686	-1.088	1.653

ar.L2.D.Settle	0.0007	0.016	0.043	0.966	-0.030	0.032

ar.L3.D.Settle	-0.0126	0.012	-1.032	0.302	-0.037	0.011

ar.L4.D.Settle	-0.0137	0.015	-0.889	0.374	-0.044	0.016

ar.L5.D.Settle	-0.0012	0.018	-0.064	0.949	-0.036	0.034

ma.L1.D.Settle	-0.2972	0.699	-0.425	0.671	-1.667	1.073

Roots

Real	Imaginary	Modulus	Frequency

AR.1	1.8918	-1.3786j	2.3408	-0.1002

AR.2	1.8918	+1.3786j	2.3408	0.1002

AR.3	-2.2701	-3.0207j	3.7786	-0.3526

AR.4	-2.2701	+3.0207j	3.7786	0.3526

AR.5	-11.0705	-0.0000j	11.0705	-0.5000

MA.1	3.3644	+0.0000j	3.3644	0.0000


Zero Mean - GARCH Model Results

Dep. Variable:	Settle	R-squared:	0.000

Mean Model:	Zero Mean	Adj. R-squared:	0.000

Vol Model:	GARCH	Log-Likelihood:	-7461.93

Distribution:	Normal	AIC:	14931.9

Method:	Maximum Likelihood	BIC:	14959.6

No. Observations:	7514

Date:	Tue, Feb 23 2021	Df Residuals:	7514

Time:	00:32:16	Df Model:	0

Volatility Model

coef	std err	t	P>|t|	95.0% Conf. Int.

omega	4.2896e-03	2.057e-03	2.085	3.708e-02	[2.571e-04,8.322e-03]

alpha[1]	0.0381	1.282e-02	2.970	2.974e-03	[1.295e-02,6.321e-02]

alpha[2]	0.0000	1.703e-02	0.000	1.000	[-3.338e-02,3.338e-02]

beta[1]	0.9536	1.420e-02	67.135	0.000	[ 0.926, 0.981]



## Conclusions

Based on your time series analysis, would you buy the yen now?

Is the risk of the yen expected to increase or decrease?

Based on the model evaluation, would you feel confident in using these models for trading?

Based on my time series analysis, I would buy the yen now as the price of the yen is expected to increase.

The risk of the yen is also expected to increase based on the Volatility.

Based on the model evaluation, I would not feel confident using these models for trading, given that the pvalues are greater than .05 for the ARIMA model




## Regression Analysis

Mean Squared Error (MSE): 0.17262635470120388

Root Mean Squared Error (RMSE): 0.4154832784856737

In sample Mean Squared Error (MSE): 0.35565249959422596

In sample Root Mean Squared Error (RMSE): 0.5963660785073426


Conclusions

This model performs better on out of sample data than on in sample data based on the mean squared error.






