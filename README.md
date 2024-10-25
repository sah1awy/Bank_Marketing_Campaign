# Bank Marketing Campaign Analysis Project

This project aims to analyze marketing campaign data and predicting term deposit subscription probability

**Marketing**: is the process of promoting and selling products or services to consumers. It involves understanding consumer needs, creating value, and establishing connections between businesses and their target audiences. <br>

**Marketing campaigns**: are characterized by  focusing on the customer needs and their overall satisfaction. Nevertheless, there are different variables that determine whether a marketing campaign will be successful or not. There are certain variables that we need to take into consideration when making a marketing campaign. <br>

**Marketing analysis**: is the process of evaluating market conditions, consumer behavior, and competitive dynamics to inform marketing strategies. It involves gathering and analyzing data to understand market trends, customer preferences, and potential opportunities. The goal is to make data-driven decisions that enhance marketing effectiveness and business performance. <br>

## Marketing Strategy Foundational Framework (The 4Ps)
- **Product**: Ensures that the business offers a product or service that meets the needs and preferences of the target market. It encompasses design, features, quality, and branding, helping to differentiate the offering from competitors.
- **Pricing**: Determines how much customers are willing to pay for the product or service. Setting the right price affects profitability, market positioning, and consumer perception. It involves strategies like discounting, premium pricing, or competitive pricing.
- **Place**: Refers to how the product is distributed and where it is available for purchase. Effective placement ensures that the product is accessible to the target audience through the right channels, whether online, in stores, or through direct sales.
- **Promotion**: Involves the communication strategies used to inform and persuade customers about the product. This includes advertising, public relations, sales promotions, and social media marketing. Promotion helps build awareness and encourages purchase decisions.


## What is a Term Deposit?
**Term deposit**: is a financial product offered by banks or financial institutions in which an individual deposits a lump sum of money for a fixed period of time (the "term") at a predetermined interest rate. During this period, the money cannot be withdrawn without incurring a penalty. At the end of the term, the individual can withdraw the initial deposit plus the interest earned.

Term deposits are considered low-risk investments and are often used as a safe way to earn interest over a specific time frame. Common examples include certificates of deposit (CDs) or fixed deposits (FDs).


## Business Model Canvas
- **Value Proposition**
- **Customers**
- **Channel**
- **Relationship**
- **Key Activities**
- **Key Resources**
- **Revenue**
- **Cost**
- **Partnership**

---

## Features Description
- **age**: (numeric)
- **job**: type of job (categorical)
- **marital**: marital status (categorical)
- **education**: (categorical)
- **default**: has credit in default? (categorical)
- **housing**: has housing loan? (categorical)
- **loan**: has personal loan? (categorical)
- **balance**: Balance of the individual.(numeric)
- **contact**: contact communication type (categorical)
- **month**: last contact month of year (categorical)
- **day**: last contact day of the week (categorical)
- **duration**: last contact duration, in seconds (numeric).     
- **campaign**: number of contacts performed during this campaign and for this client (numeric)
- **pdays**: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
- **previous**: number of contacts performed before this campaign and for this client (numeric)
- **poutcome**: outcome of the previous marketing campaign (categorical)
- **y**: has the client subscribed a term deposit? (binary)

<b style="color: green;">Important note: Duration attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.</p>

<b style="color: green;">Check all the information about the data and how I managed to make decisions.(https://archive.ics.uci.edu/dataset/222/bank+marketing).</p>

---

## Insights from the data
- **Blue-collar workers and entrepreneurs are unlikely to invest in term deposits, while students and retirees are the most likely to do so.**
- **People with tertiary education tend to invest in term deposits more than others.**
- **People who have a housing loan tend not to have a term deposit.**
- **People who have loans tend not to have a term deposit.**
- **People tend to make term deposits in December, March, September, and October.**
- **People who have been targeted by successful marketing campaigns tend to invest in term deposits.**
