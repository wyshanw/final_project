Note for data cleaning
================
11/10/2021

### Insurance

-   `insuredgateway`: Have health insurance?

<!-- -->

    1=Yes
    2=No
    .d=Don’t know
    .r=Refused

-   `insure`: Type of health insurance coverage

<!-- -->

    1=Employer
    2=Self-purchase
    3=Medicare
    4=Medicaid/Family Health+
    5=Milit/CHAMPUS/Tricare
    6=COBRA/Other
    7=Uninsured
    .d=Don’t know
    .r=Refused
    .=Missing

-   `sickadvice`: when sick, where usually go?

<!-- -->

    1= A private doctor,
    2= Non-retail clinic,
    3= Urgent Care Center,
    4= Hospital ED,
    5= Retail clinic,
    6=Alternative health care provider,
    7= Family/friend/self/ resources,
    8= Other,
    9= No usual place,
    .d=Don’t know,
    .r=Refused, 
    .=Missing/not asked

-   `didntgetcare`: Was there a time in the past 12 months when you
    needed medical care but did NOT get it?

<!-- -->

    1=Yes
    2=No
    .d=Don’t know
    .r=Refused

### Smoking related

-   `smoker`: Whether smoker (smoked at least 100 cigarettes in your
    entire life?)

<!-- -->

    1= Never
    2= Current
    3= Former
    .d= Don’t know
    .r= Refused

-   `everyday`: Smoke every day vs some days

<!-- -->

    1= Yes, every day
    2= No, some days
    .d= Don’t know
    .r= Refused
    . = Missing/Not asked

-   `numberperdaya`: average cigs smoked per day, continuous

-   `cost20cigarettes`: Cost of 20 cigarettes (one pack), continuous

<!-- -->

    d= Don’t know
    .r= Refused  
    . = Missing/Not asked

### Others

-   `agegroup` age groups

<!-- -->

    1=18-24yrs
    2=25-44 yrs
    3=45-64 yrs
    4=65+ yrs
    .d=Don’t know
    .r=Refused

-   `generalhealth`: general health status (self evaluated)

<!-- -->

    1=Excellent, 
    2=Very good, 
    3=Good, 
    4=Fair, 
    5=Poor, 
    .d=Don’t know,  
    .r= Refused

-   `imputed_povertygroup`: Household annual income from all sources
    (FPL: federal poverty level)

<!-- -->

    1= <100% FPL
    2=100 - <200% FPL
    3=200 - <400% FPL
    4=400 - <600% FPL
    5= >600% FPL

### New Factors

-   `sex`

<!-- -->

    1= male
    2= female

-   `bmi`

<!-- -->

    15-55

-   `child`

<!-- -->

    1= yes
    0= no
