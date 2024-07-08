# [data_cleaning_walkthrough](./DataCleaning_Example.html)

_Before we can use our dataset to tell a story, we first need to make sure the words we use to tell the story make sense._

What I mean by that is: We need to ensure our dataset is clean! This means:
- Sensible data types
- Remove special characters which impact readability
- Remove or normalize blanks
- Distinguish between NA's, nulls, blanks

We will use a sample dataset containing interview respondents from Chicago, New York, and Los Angeles. The dataset contains these columns:

-   *ID:* sequential ID from interview respondents
-   *birth_date:* mm/dd/yyyy format
-   *gender_string:* Respondent gender identity
    -   Male
    -   Female
    -   Questioning
    -   Non-binary/Genderqueer/Third gender
    -   Prefer Not to Say
-   *gender_modality:* Flag denoting whether respondent identifies as transgender
    -   1 = Transgender
    -   2 = Cisgender
-   *sexuality:* Sexual Identity
    -   1 = Gay
    -   2 = Lesbian
    -   3 = Bisexual
    -   4 = Queer
    -   5 = Questioning
    -   6 = Heterosexual
-   *race_eth:* race-ethnicity (Internal: See Codebook for definitions)
-   *latinx_hispanic:* Yes/No flag Hispanic status
    -   1 = Yes
    -   0 = No
-   *location:* Numeric code for cities
    -   1 = Chicago
    -   2 = New York
    -   3 = Los Angeles
-   *location_string:* Readable city variable
-   *interview_year:* Year of interview ranging from 2010-2019
-   *interview_month:* Numerical month indicator (Gregorian calendar)
    -   1 = January ...
-   *interview_date:* mm/dd/yyyy format
-   *dctr_6months:* Flag indicating if interviewee visited the doctor in the 6 months prior to the **interview_date**
-   *zip_code:* Residential ZIP code of interviewee
