##LINEAR REGRESSION

class LinearRegression(sklearn.base.MultiOutputMixin, sklearn.base.RegressorMixin, LinearModel)<br>
   LinearRegression(*, fit_intercept=True, normalize='deprecated', copy_X=True, n_jobs=None, positive=False)<br>
   
   Ordinary least squares Linear Regression.<br>
   
   LinearRegression fits a linear model with coefficients w = (w1, ..., wp)<br>
   to minimize the residual sum of squares between the observed targets in<br>
   the dataset, and the targets predicted by the linear approximation.<br>
 
   Parameters
   ----------
   fit_intercept : bool, default=True
       Whether to calculate the intercept for this model. If set
       to False, no intercept will be used in calculations
       (i.e. data is expected to be centered).
   
   normalize : bool, default=False
       This parameter is ignored when ``fit_intercept`` is set to False. <br>
       If True, the regressors X will be normalized before regression by<br>
       subtracting the mean and dividing by the l2-norm.<br>
       If you wish to standardize, please use<br>
       :class:`~sklearn.preprocessing.StandardScaler` before calling ``fit``<br>
       on an estimator with ``normalize=False``.<br>
       Returns
        -------
       self : estimator instance
           Estimator instance.
 
 
 Learn more from : https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
