<center><h2>Potential Customer Profit Calculation by Rule Based Classification</h2></center>

---

### Problem
A game company wants to create level-based new customer definitions (personas) by using some features of
its customers, and to create segments according to these new customer definitions and to estimate how much
the company can earn on average from new customers based on these segments.

**For example:** The company wants to determine how much a 25-year-old male user from Turkey, who is an IOS user, 
can earn on average to the company.

---

### Dataset
Persona.csv data set contains the prices of the products sold by an international game company and some demographic
information of the users who buy these products. The data set consists of records created in each sales transaction.
This means that the table is not singularized. In other words, a user with certain demographic characteristics may
have made more than one purchase.

* **Price:** Customer's Spending Amount
* **Source:** Customer's Device
* **Sex:** Customer's Gender
* **Country:** Customer's Country
* **Age:** Customer's Age

---
`View of dataset before process`

    PRICE   SOURCE    SEX    COUNTRY   AGE
     39     android   male     bra     17
     39     android   male     bra     17
     49     android   male     bra     17
     29     android   male     tur     17
     49     android   male     tur     17

---
`View of dataset after process`

    CUSTOMER_LEVEL_BASED            PRICE       SEGMENT
    bra_android_female_0_18        35.6453         B
    bra_android_female_19_23       34.0773         C
    bra_android_female_24_30       33.8639         C
    bra_android_female_31_40       34.8983         B
    bra_android_female_41_66       36.7371         A
---
### Installation
1. Clone this repository

```
https://github.com/nedimcanulusoy/Rule-Based-Classification.git
```

2. Change directory to the cloned repository

```
cd Rule-Based-Classification
```

3. Open the notebook and run the cells

---

### Disclaimer

The data set is not included due to General Data Protection Regulation (GDPR) rules.

---
