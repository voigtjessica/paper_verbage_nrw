# vergabe_nrw_correcao

### When this data was collected?
07 /01/2021  , see Vergabe NRW CSV file

### Step 1: Defining the problem: What we want to see with this data?
    
During almost two years, the Federal and regional governments in Germany needed to aqquire a series of things to deal with COVID-19 pandemics. Due to factors such as lack of vendors, scarcity of material, urgency of purchesing among others, it is expected that many of these purchases are expected to have been made under extraordinary arrangements, involving exclusion from bidding, among others. But should all the purchases be made in this regime.

**We want to discover if there is red flags for mismanagement in COVID-19 measures by the government of Nordrhein-Westfallen in Germany.** To do that, we need to answer the following questions:

> 1. Are all the purchases regarding COVID-19 available ?
> 2. How many purchases were made on an extraordinary basis (no bidding, direct negotiation with seller, etc) ?
> 3. When these purchases were made?
> 4. By the time of extraordinary purchases, was there actually a lack of vendors of urgency of for this purchase?

And how can we beggin to answer those questions?

1. Are all the purchases regarding COVID-19 available ?
    - 1.1 Look at CPV Codes
    - 1.2 Compare the purchases made it here with external databases (there is another Vergabe portal)
    - 1.3 Validate the data with local data (for example, the city of Köln, which might have their own transparency portal)
    - 1.4 Validate the data of a municipality with a Fredom of Information Request
<br><br>
2. How many purchases were made on an extraordinary basis (no bidding, direct negotiation with seller, etc) ?
    - 2.1 See if the data from Vergabe NRW has information about the bidding format and type of contract
<br><br>    
3. When these purchases were made?
    - 3.1 See if the data from Vergabe NRW has information about the data of purchase 
    - 3.2 See if the data from Vergabe NRW has information about the date of contracts
<br><br>
4. By the time of extraordinary purchases, was there actually a lack of vendors of urgency of for this purchase?
    - 4.1 Cross the date information with COVID-19 cases in Germany
    - 4.2 Cross the date information with Hospital Capacity
    - 4.3 See if we find intresting information, milestones or similar information in news articles

# Practical questions about the data:

### Step 2: Exploring the data

In this specific notebook I'll see the state of art of the data collected from Vergabe NRW and see what problems does it has. The following will be verified:



1. Is there duplicates?
2. Is there missing data?
    - what is this missing data doing in my db?
    
3. Is there encoding problem?
4. Do the cities have always the same name? Or do they have different writings?
5. Is there any information regarding costs? Are the derzeitige Werten (valores correntes)?
6. What each collumn means?
7. What each observation is?
8. Which of the above questions (Step 1) can we answer?
