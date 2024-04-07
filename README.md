# PRODIGY_ML_TRACK_1
🪢 This is a model which was produced to predict the prices of houses by using the concept of machine learing.

🪢 Under this project I have used numpy, pandas, skit-learn and also matplot in order to satsify and meet the conditions of this project.

**STEP I: Testing Data**
   🪢Under this section, I have implemnented Pandas to read the files and check for any errors in our data set and also select the varibales in which the prediction of price was going to be undertaken.
   
**STEP II: Data Visualization**
   🪢Under this section , I have implmented the use of Matplot and also Color map inorder to draw relationship between the sale price with the other selected variable in STAGE 1.
   🪢 I have excluded any type of non numerical and irrelvant data inorder to make sure there were no errors.
   🪢 Under the division of the heat map, we have used seaborn module to make a coorelation factor.
   🪢 Also we have implmented the use of msno to see the matrix grid of the whole data set under the shade.
   
**STAGE III: Model Building**
 🪢 Under this , we have set 2 varibales for our linear regression modeling.
   🪢 X = train_set[['LotArea','YearBuilt','YrSold','BsmtFullBath', 'BsmtHalfBath', 'FullBath', 'BedroomAbvGr']]
       y = train_set[['SalePrice']]
      🪢 Under this two varibales, we have set the machine to predict the price of the sale using the varibles that are given in X.
      🪢 Also we have set the real price of the houses to be set as constant under the y.
  2024 @ Addis Ababa , Ethiopia, by Nahom Wondale 
 
   
