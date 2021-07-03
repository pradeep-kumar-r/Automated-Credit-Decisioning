# Case Study - Create automated underwriting system

**About:**
ABC Payments Bank is a mobile-only bank. Their primary business is to give out digital credit cards to eligible users with a credit limit ranging from $1000 to $8000 all over the world. These digital credit cards are issued within an hour after filling up a form in the Bank’s Mobile App called DigiCard.

This product provides a very good revenue to the banks, however, it’s a challenging task for them to decide who should they approve for the card and who to reject. You have to help this bank decide how can they confidently take this decision based on the experience they had in the past. 
 
Using the attached dataset which contains historical data about bank’s old customers, the problem has two primary goals: 
1. Whom to approve or reject for the credit card? 
2. How much credit limit to give if approved? 

**Data:**
The CSV file has following columns:
● user_id
● gender
● date_of_birth
● workclass
● education_level
● education_num : education_level as a continuous variable. Eg, Masters(14) >
Bachelors(13)
● marital_status
● occupation
● relationship : current relationship status
● capital_gain : capital gain made in the last financial year in USD through investments
● capital_loss : capital loss in the last financial year in USD through investments
● Hours_per_week : Number of hours worked by the person per week.
● approved : Whether customer was approved for the Credit Card.
● address
● Email

These data points are retrieved from a credit bureau (eg, CIBIL). A Bureau is a central
party which has all the data related to credit history of a customer. Typically, a financial institution (eg, a bank) requests a report from bureau from credit history and score for purposes like a Loan, Credit Card etc.
● Inquiry_purpose_code : Purpose of enquiry from the bureau
● Institute_type : Type of institute that requested the bureau
● Account_type : Type of account of the customer for requesting from the bureau
● Asset_class_cd : Current state of the assets of the customer
● Asset_code : Type of ownership of the customer
● Portfolio_type : Type of portfolio

Refer to the data dictionary for more details on some of the fields.

**Note:**
The problem statement and data set is hypothetical
