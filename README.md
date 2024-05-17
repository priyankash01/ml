# mushroom classification

Mushrooms have been consumed since earliest history. The word Mushroom is derived from the French word for Fungi and Mold. Now-a-days, Mushroom are popular valuable food because they are low in calories, carbohydrate, Fat, sodium and also cholesterol free. Besides this, Mushroom provides important nutrients, including selenium, potassium, riboflavin, niacin, Vitamin D, proteins and fiber. All together with a long history as food source. Mushroom are important for their healing capacity and properties in traditional medicine. It has reported beneficial effects for health and treatment of some disease. Many nutraceutical properties are described in Mushroom like cancer and antitumor attributes. Mushroom act as antibacterial, immune system enhancer and cholesterol lowering Agent. Additionally, they are important source of bio-active compounds. This work is a machine learning model that classifies mushrooms into 2 classes: Poisonous and Edible depending on the features of the mushroom. During this machine learning implementation, we are going to see which features are important to predict whether a mushroom is poisonous or edible.

The Audubon Society Field Guide to North American Mushrooms contains descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom (1981). Each species is labelled as either definitely edible, definitely poisonous, or maybe edible but not recommended. This last category was merged with the toxic category. The Guide asserts unequivocally that there is no simple rule for judging a mushroom's edibility, such as "leaflets three, leave it be" for Poisonous Oak and Ivy.

The main goal is to predict which mushroom is poisonous & which is edible.
This project aims at developing a machine-learning algorithm that will determine if a certain mushroom is edible or poisonous by its specifications like cap shape, cap color, gill color, etc. using different classifiers.

To do so, I have used the following classification methods:

1. Decision Tree Classifier
2. Logistic Regression Classifier
3. k-Nearest Neighbor Classifier
6. Random Forest Classifier

 DATASET : FROM THE KAGGLE WEBSITE Kaggle Link : https://www.kaggle.com/uciml/mushroom-classification

 Data Set Description :
   Attribute Information: (classes: edible=e, poisonous=p)

#     cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s

#     cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s

#     cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y

#     bruises: bruises=t,no=f

#     odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s

#     gill-attachment: attached=a,descending=d,free=f,notched=n

#     gill-spacing: close=c,crowded=w,distant=d

#     gill-size: broad=b,narrow=n

#     gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y

#     stalk-shape: enlarging=e,tapering=t

#     stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?

#     stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s

#     stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s

#     stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y

#     stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y

#     veil-type: partial=p,universal=u

#     veil-color: brown=n,orange=o,white=w,yellow=y

#     ring-number: none=n,one=o,two=t

#     ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z

#     spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y

#     population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y

#     habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d

**** IN THIS DATASET WE HAVE 8124 ROWS AND 23 COLUMNS ****

 Architecture :
  
   
 <img width="743" alt="ARCHI" src="https://github.com/priyankash01/Read-me/assets/142376337/3fd573c8-3994-494a-a7c6-ae24aca90515">

Web Interface : 


<img width="916" alt="Screenshot 2024-05-16 at 7 29 51 PM" src="https://github.com/priyankash01/Read-me/assets/142376337/d3cdfeed-f641-4306-8d07-8fbb8841568a">

Summary/ result

The model predict which mushroom is poisonous & which is edible. 

prediction window:

<img width="717" alt="prediction" src="https://github.com/priyankash01/ml/assets/142376337/cf73222b-a516-47c5-9409-640df698a67d">



