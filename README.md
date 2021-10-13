# JOB-A-THON-2021
Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs.

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities.

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc. Your task is to predict the store sales for each store in the test set for the next two months. Data Dictionary Train Data Variable Definition ID Unique Identifier for a row Store_id Unique id for each Store Store_Type Type of the Store Location_Type Type of the location where Store is located Region_Code Code of the Region where Store is located Date Information about the Date Holiday If there is holiday on the given Date, 1 : Yes, 0 : No Discount If discount is offered by store on the given Date, Yes/ No #Orders Number of Orders received by the Store on the given Day Sales Total Sale for the Store on the given Day

Test Data Variable Definition ID Unique Identifier for a row Store_id Unique id for each Store Store_Type Type of the Store Location_Type Type of the location where Store is located Region_Code Code of the Region where Store is located Date Information about the Date Holiday If there is holiday on the given Date, 1 : Yes, 0 : No Discount If discount is offered by store on the given Date, Yes/ No.
The evaluation metric for this competition is MSLE * 1000

# Model Used
RandomForestRegressor

# Features Used
Score - 207.6915171682                             Private Leaderboard Rank - 5
I used 3 Features from the given data (Store_id,Holiday,Discount ) and 8 new features t1,t2,t3,t4,t5 which are last 5 days sales and avg30,avg20,avg10 average of last 30,20,10 days sales respectively .<br><br>

