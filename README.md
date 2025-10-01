# Bank-Marketing-Campaign-Analysis

## Objective

Analyze a marketing campaign dataset from a bank to understand client demographics, products, loan status, campaign effectiveness, and customer conversion for term deposits.

## Data Preparation

Imported and cleaned dataset (45,205 records). Preprocessing covered missing values, encoding, and relevant feature selection.

## Exploratory Data Analysis (EDA)

### Demographics
- **Age**: Mean age is ~41 years, with a range from 18 to 95 years
- **Job**: Most clients are blue-collar workers, management, or technicians
- **Marital Status**: Majority are married, followed by single and divorced
- **Education**: Secondary education is most common, followed by tertiary and primary

### Financial Attributes
- Majority of clients have positive account balances; some extreme outliers present
- 1.8% of clients are in credit default
- 55% have a housing loan
- 16% have a personal loan

### Campaign Attributes
- Main contact channels: cellular, telephone, or unknown
- Most contacts occur during May, July, and August
- Typical last contact duration: ~258 seconds
- Mean number of campaign contacts: ~2.8 contacts per client
- Only 1,511 clients had a previously successful campaign

## Target Outcome

Approximately 12% of clients subscribed to a term deposit.

## Influencing Factors

Correlation analysis using heatmaps reveals:
- **Duration of last contact** is the strongest predictor of subscription
- Categorical factors significantly affecting conversion:
  - Job profile
  - Education level
  - Previous campaign outcome
  - Month of contact
  - Contact type

### Segmentation Insights
- Subscription rates are highest for students and retirees
- Subscription rates vary widely by:
  - Job type
  - Education level
  - Loan status
  - Campaign attributes

## Conclusion

Successful term deposit conversion strongly depends on:
- Contact duration with clients
- Job profile
- Education level
- Loan status
- Previous campaign outcomes

These insights can guide targeting and personalization strategies in future marketing campaigns to improve conversion rates.

## Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning and modeling
