# Predicting-Flood-in-Malawi
In recent decades, countries across Africa have experienced an increase in the frequency and severity of floods. Malawi has been hit with major floods in 2015 and again in 2019. In fact, between 1946 and 2013, floods accounted for 48% of major disasters in Malawi. The Lower Shire Valley in southern Malawi, bordering Mozambique, composed of Chikwawa and Nsanje Districts is the area most prone to flooding.

The objective of this challenge is to build a machine learning model that helps the extent of floods in southern Malawi.
</br>

# Data
Elevation: Mean elevation over the rectangle, based on this dataset in Google Earth Engine.
Dominant Land Cover Type: Most areas are predominantly grasslands, savannah or cropland. You can find the full list of land cover types here in the ‘LC_Type1 Class Table’.
Weekly Precipitation: Historical rainfall data for each rectangle, for 18 weeks beginning 2 months before the flooding. Rainfall estimates from this dataset in Google Earth Engine.
The X, Y coordinates given represent a rectangle 0.01 degrees on each side, centered on that X-Y location.
The target is the percentage of the given rectangle that was flooded, with a value between 0 and 1.
</br>
# results
we used the Following Models And give us the Following Results:
1.Decision Tree :
train acc:100.00 %
test acc:  71.28 %
rmse:  0.12 %
</br>
2.SVM:
train acc:43.71 %
test acc:  43.34 %
rmse:  0.17
</br>
3.Linear Regression:
train acc:16.61 %
test acc:  16.61 %
rmse:  0.21
</br>
4.Lasso Regression:
train acc:16.61 %
test acc:  16.95 %
rmse:  0.21
</br>
4.Ridge Regression:
train acc:16.61 %
test acc:  16.92 %
rmse:  0.21
</br>
5.Random Forest:
train acc:96.41 %
test acc:  83.51 %
Random Forest Regressor No. of features are :  21
rmse:  0.09
