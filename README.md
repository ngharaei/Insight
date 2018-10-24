# Insight

Obesity is a major health problem, affecting every 1 out of 3 Americans and contributing to leading causes of death in developed countries. Aside from its detrimental effects on health, Obesity has a significant effect on the United States economy. The estimated US annual health care costs of obesity-related illnesses is $190.2 billion or nearly 21% of annual medical spending (which is suspected to increase approximately $1.24 billion annually until 2030). Therefore, helping to reduce this epidemic will not only improve individual’s health and quality of life, it will be beneficial to the US economy.

A surprising observation was made after the Dutch famine of 1944 (also known as the hunger winter). During this exceptionally harsh winter, German blockade of food and fuel (to punish the reluctance of the Dutch to help Nazi war efforts) led to the severe starvation of people in the occupied regions of Netherlands and 22000 deaths. Not surprisingly, many children conceived during this time were born small and underweight. However, growing up these children had increased risk of obesity and diabetes. It has been suggested that the poor maternal nutritional intake had caused these children to increase their caloric storage and minimize energy expenditure leading to their increased risk of obesity. Further studies on this hypothesis have proven difficult since ethical considerations limit the extent of experimental manipulations that can be performed on humans.

Here, I used the already available datasets of health measures to test this hypothesis. For this project, I used the Community Health Status Indicators (CHSI) datasets, which contain more than 200 different key health measures for each of the 3,141 US counties, to investigate the correlation between fetal malnutrition and occurrence of obesity. The CHSI datasets have been provided by Centers for Disease Control and Prevention (CDC) to encourage the involvement of the members of the community in the battle against obesity, as well as heart disease and cancer. One of the indicators provided in these datasets is the percentage of underweight (<2.5 kg) newborns (LBW) in each of the US counties. This measurement can be used as a direct indicator of low prenatal nutrition. These datasets also provide the percentage of obesity, diabetes and some other diseases in each of the US counties. 

I started my investigation by examining the correlation between low weights of infants at birth (as an indicator of low prenatal nutrition) with the prevalence of obesity and diabetes in different US communities (Figures 1 and 2 respectively).


<a href="http://tinypic.com?ref=amz3ap" target="_blank"><img src="http://i63.tinypic.com/amz3ap.png" border="0" alt="Image and video hosting by TinyPic"></a>
Figure 1: Percentage of obesity in the US counties plotted against percentage of underweight births (<2.5 kg) in the same counties. 


This analysis showed that there is a positive correlation (Pearson correlation coefficient of ~ 0.3) between the percentage of underweight births (<2.5 kg) in each of the US counties and the percentage of obesity and diabetes in the same counties .
 

<a href="http://tinypic.com?ref=5kkl5c" target="_blank"><img src="http://i63.tinypic.com/5kkl5c.png" border="0" alt="Image and video hosting by TinyPic"></a>
Figure 2: Percentage of diabetes in the US counties plotted against percentage of underweight births (<2.5 kg) in the same counties.

This further raised the question of whether populations with fetal malnutrition, indicated with Low Birth Weight, would have higher risk of other metabolic syndromes. Thus, I investigated correlation between Low Birth Weight (LBW) and frequency of other metabolic syndromes for which the data was available in this database, namely, High Blood Pressure and Coronary Heart Disease. I also invesitgated the correlation of LBW and non-metabolic diseases as negative control. 

<a href="http://tinypic.com?ref=34zxh80" target="_blank"><img src="http://i64.tinypic.com/34zxh80.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
Figure 3: Correlation between underweight births (<2.5 kg) and different metabolic or non-metabolic syndormes in the same counties. 


This analysis further supports the hypothesis that poor fetal nutrition (which is the major cause of low birth weight) is correlated with the risk of metabolic disorders, suggesting that availability of adequate nutrition during pregnancies is a potentially powerful avenue for combating obesity and diabetes in the US communities as well as other metabolic disorders. This hypothesis is corroborated by the weak correlation between LBW and non-metabolic disorders, which furhter supports that LBW only increases the risk of metabolic disorders in adults and not the risk of non-metabolic disorders.


Low income could be a major factor contributing to fetal malnutrition. To investigate this, I plotted the percentage of pverty indicator as well as LBW across different US counties. 

<a href="http://datawrapper.dwcdn.net/Y7iaS/2/" target="_blank"><img src="http://datawrapper.dwcdn.net/Y7iaS/2/" border="0" alt="Image and video hosting by TinyPic"></a>

<iframe id="datawrapper-chart-Y7iaS" src="http://datawrapper.dwcdn.net/Y7iaS/2/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="400"></iframe>

<iframe id="datawrapper-chart-Y7iaS" src="//datawrapper.dwcdn.net/Y7iaS/2/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="400"></iframe><script type="text/javascript">if("undefined"==typeof window.datawrapper)window.datawrapper={};window.datawrapper["Y7iaS"]={},window.datawrapper["Y7iaS"].embedDeltas={"100":400,"200":400,"300":400,"400":400,"500":400,"700":400,"800":400,"900":400,"1000":400},window.datawrapper["Y7iaS"].iframe=document.getElementById("datawrapper-chart-Y7iaS"),window.datawrapper["Y7iaS"].iframe.style.height=window.datawrapper["Y7iaS"].embedDeltas[Math.min(1e3,Math.max(100*Math.floor(window.datawrapper["Y7iaS"].iframe.offsetWidth/100),100))]+"px",window.addEventListener("message",function(a){if("undefined"!=typeof a.data["datawrapper-height"])for(var b in a.data["datawrapper-height"])if("Y7iaS"==b)window.datawrapper["Y7iaS"].iframe.style.height=a.data["datawrapper-height"][b]+"px"});</script>
Figure 4. Choropleth map showing the distribution of "poverty" across different US. counties


<iframe id="datawrapper-chart-mqyFX" src="//datawrapper.dwcdn.net/mqyFX/1/" scrolling="no" frameborder="0" allowtransparency="true" style="width: 0; min-width: 100% !important;" height="400"></iframe><script type="text/javascript">if("undefined"==typeof window.datawrapper)window.datawrapper={};window.datawrapper["mqyFX"]={},window.datawrapper["mqyFX"].embedDeltas={"100":426,"200":400,"300":400,"400":400,"500":400,"700":400,"800":400,"900":400,"1000":400},window.datawrapper["mqyFX"].iframe=document.getElementById("datawrapper-chart-mqyFX"),window.datawrapper["mqyFX"].iframe.style.height=window.datawrapper["mqyFX"].embedDeltas[Math.min(1e3,Math.max(100*Math.floor(window.datawrapper["mqyFX"].iframe.offsetWidth/100),100))]+"px",window.addEventListener("message",function(a){if("undefined"!=typeof a.data["datawrapper-height"])for(var b in a.data["datawrapper-height"])if("mqyFX"==b)window.datawrapper["mqyFX"].iframe.style.height=a.data["datawrapper-height"][b]+"px"});</script>
Figure 5. Choropleth map showing the distribution of "Low Birth Wight (<2.5 kg)" across different US. counties



As you can see in Figures 4 & 5, counties with higher percentage of poverty are often those that suffer from higher percentage of LBW (specially in the counties in the south and south east of the US). This further supports the correlation between poverty and fetal malnutrition which in turn could lead to metabolic disorders in adulthood. The distribution of food insecurity rates across the US also aligns with the LBW distribution, further supporting this hypothesis (Figure 6).

<a href="http://tinypic.com?ref=f26mj7" target="_blank"><img src="http://i65.tinypic.com/f26mj7.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
Figure 6. Choropleth map showing the distribution of food insecurity across different US. counties


Additional studies, using similar strategies can help pinpoint the correlation between the effect of other metabolic imbalance factors and metabolic diseases paving the way for development of predictive indicators of metabolic disorders. In addition, in this study I only focused on datapoints  for one year that were released by CDC. Apparently CDC does have similar datasets for additional years which will release by request. Having multiple datapoint would allow to study the timeseries and get a better picture of the effect of LBW on the risk of diseases in adults. I have requrested this additional datasets and will further complete my analysis once I recieve those datasets. 
Another interesting dataset that I'm would like to look into is from the EARLY GROWTH GENETIC CONSERCIUM  (http://egg-consortium.org) which provides data on human genome loci that have an impact on a variety of traits related to early growth. It would be interesting to see whether genetic variation have any effect on LBW and obesity and to what extent these phenotypes are defined by genetic and environmental factors. 


the combination of insights gained from these datasets, would give us a better understanding on the extent that fetal malnutrition could have on the degree of metabolic disorders in adults and equip us with a better understanding of factors that contribute to these diseases. Such insights could be used to initiate better programs to help to reduce risk facotrs in pregnant women and provide less costly preventative opportunies in combating metabolic disorders. 
