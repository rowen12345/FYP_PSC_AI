Final Year Project – AI Modeling of Perovskite Solar Cell IV Curves

Conducted research under Erik Birgersson at National University of Singapore, developing machine learning models in MATLAB to predict current–voltage (IV) curves of perovskite solar cells using 31 physical input parameters.

Key Contributions

Dimensionality Reduction of IV Curves
Reduced the number of predicted I–V curve points from 45 to 10 while maintaining prediction accuracy, significantly improving computational efficiency.

Curve Reconstruction via Interpolation
Applied Piecewise Cubic Hermite Interpolation (PCHIP) and spline interpolation to reconstruct full I–V curves from predicted points, achieving a mean RMSE of ~5 across 6,600+ predicted curves. Implemented convergence techniques to further improve model accuracy.

Neural Network Optimization
Performed extensive hyperparameter tuning (neurons, hidden layers, activation functions, regularization), requiring ~200 evaluations per model and 4–5 hours of training time to identify optimal configurations.

Interactive Prediction Tool
Developed a MATLAB App Designer application that allows users to input perovskite solar cell properties and generate real-time IV curve predictions through the trained model.
