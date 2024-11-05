java c
AD680 Global Supply Chains 
Problem Set #2: Inventory Aggregation 
Consider the information and data presented in the textbook case study “Should Packing Be Postponed to the DC [Distribution Center]?” (Page 356 in the textbook), that concerns inventory management at Penang Electronics, where orders areplaced weekly, and the lead time for receiving orders is 9 weeks. Pay close attention to the details of the case study, but ignore the list of questions posed on Page 357.
For this assignment, do the following:
Compare the two alternatives under consideration for final labeling and packaging:
1.    At the production faculty in Malaysia before being shipped to the DC (the current approach) and
2.    At the DC in St. Louis (i.e., postponing labeling and packaging until just before shipment).
The comparison should consider the savings in annual holding cost with aggregation compared to the increased production costs of aggregation.  When determining if aggregation is warranted, note that how inventory is managed does not need to be consistent across the three products (computers, printers, scanners).  That is, aggregation maybe worthwhile for only one or two of the three products, and this approach can be implemented.
When analyzing the two alternatives, use a target product fill rate of 99%. Assume that the demand across the four customers is independent but that demand variation is perfectly correlated across weeks.
The assessment of this work will be based on the accuracy and clarity of your spreadsheet. 
E-mail one Excel file, using a filename Lastname_3.
TIPS: 
Approach 1: At the production faculty in Malaysia before being shipped to the DC (the current approach) We are given that

Computers 
Printers 
Scanners 
Forecast Wk 
Sigma Wk 
Forecast Wk 
Sigma Wk 
Forecast Wk 
Sigma Wk 
Target 
1,000 
700 
2,000 
1,000 
4,000 
1,000 
BBY 
700 
600 
1,500 
800 
4,500 
900 
OM 
800 
600 
1,200 
600 
2,000 
700 
Staples 
500 
400 
900 
500 
1,400 
500 
Let us first work on computers. We would like to find out the safety stock (ss) for the computers for each customer. Let us focus on Target.
The formula for ss is
ss = kσT+L 
k is the constant that we get from f(k) which is given by 
f (k) = cvT+L/1− fr
where cvt+L  isthe coefficient of variation during the RLTD period and σT+L is the standard deviation during the RLTD period. We are given in the problem that the fill-rate (fr) is equal to 0.99.
cvt+L = σT+L/  μT+L   so let us first find the μT+L  and σT+L   for computers.
We are given that T = 1 week and L =9 weeks so T+L = 10 weeks. μT+L (Target)= 1,000*10=10,000How do we find σT+L ? It is important to realize that σT+L  isthe standard deviation over 10 weeks. And we are given the information that d代 写AD680 Global Supply Chains Problem Set #2: Inventory AggregationProlog
代做程序编程语言emand variation is perfectly correlated across weeks. Therefore, we  use the formula:
σT+L = σ1 +σ2  + . . . +σT+L 
σT+L (Target) = 700*10 = 7,000. Then,
cvt+L = σT+L / μT+L  = 7,000/10,000= 0.7
f(k) = (1-0.99)/0.7 = 0.014 k = 1.808.
ss =(1.808)*(7,000) = 12,656.
Now, you find the ssvalues for BBY, OM, and Staples for computers (using the above approach) and then you compute the totalss for computers.
Totalss for computers = ss(Target)+ ss(BBY) + ss(OM) + ss(Staples)
Holding cost for computers under Approach 1 = (Totalss for computers)* (cost per computer) * (30%).
Approach 2: At the DC in St. Louis (i.e., postponing labeling and packaging until just before shipment).
In this approach, we will not consider each customer (i.e., Target, BBY, OM, Staples) individually.
Instead, we will be looking at the aggregate demand for each product. Again, let us just focus on the computers.
What is the aggregate demand for computers? It is the summation of demand for Target, BBY, OM, and Staples. It is 1,000+700+800+500 = 3,000 = μT.
What is the aggregate standard deviation for computers across the customers. Here we will be using the information given to us that “Assume that the demand across the four customers is
independent” .  We will be using the following formula.
2             2            2                        2
σT = σ1  + σ2  + …+ σk 
σ!(2)  = 7002  + 6002  + 6002  + 4002   =  1,370,000
Then, σT =1,170.
Now, we need to find the mean and the standard deviation over the RLTD period.
μT+L = 3,000*10=30,000How do we find σT+L ? It is important to realize that σT+L  isthe standard deviation over 10 weeks. And we are given the information that demand variation is perfectly correlated across weeks. Therefore, we  use the formula:
σT+L = σ1 +σ2  + . . . +σT+L 
σT+L = 1,170*10 = 11,700.
cvt+L = σT+L / μT+L  = 11,700/30,000= 0.39
f(k) = (1-0.99)/0.39 = 0.026
k=1,552.
ss =(1.552)*(11,700) = 18,158.
Holding Cost  = ss * (Cost per computer)*(30%).
Now, there is an extra cost associated with aggregating. In particular, we are given that per unit, we pay $2 more if we aggregate. How much more do we pay?
$2 * (aggregated forecast/week for computers) * 52 weeks/year
We multiply by 52 because there are 52 weeks in a year and the holding cost is a yearly cost – we would like to add holding cost to the extra cost we calculate here so we want them to have similar units.
Total cost = Holding cost + Extra cost
The improvement in the cost with aggregating for computers would be found by Total cost (Approach 2)  - Holding cost (Approach 1)
For computers: the improvement will be $6.910,200.
For printers: the improvement will be $1,908,350.
For scanners: the improvement will be -$451,840.
So, it does not make sense to aggregate for scanners.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
