# Overview of the CSV Files for Control and Experimental Groups

This repository includes two CSV files containing data for both the control group and the experimental group, with 125,000 records each. The files are structured to capture various aspects of user interactions with a website login process. Each file represents the data collected during the study, including user details, group assignments, and interaction metrics.

## Data Fields

Each CSV file contains the following fields:

- **user_id**: A unique identifier for each user. This helps distinguish each user in the dataset.
- **group**: Indicates whether the user belongs to the control group or the experimental group. The value is either "control" or "experimental".
- **department**: The department that each user is part of. This could represent different divisions or teams within an organization.
- **timestamp**: A timestamp that records the exact time when a user interacted with the website. This helps in analyzing peak usage times and trends.
- **landing_page**: The page where the user initially landed:
  - "old page" for users in the control group.
  - "new page" for users in the experimental group.
- **satisfaction_rating**: A numerical rating provided by the user, ranging from 1 to 10, reflecting their satisfaction with the login experience. A score of 1 represents "Very Dissatisfied," while a score of 10 represents "Very Satisfied."
- **auth_time_seconds**: The time taken by each user to complete the authentication process, measured in seconds. This metric helps to evaluate the efficiency of the login process across the two groups.

## Purpose of the Data

The data in these CSV files allows for a detailed comparison between the control group and the experimental group. Specifically, it helps to analyze:

- **User Satisfaction**: By comparing satisfaction ratings, we can assess the impact of changes (e.g., new login methods) on user satisfaction.
- **Authentication Time**: The `auth_time_seconds` field allows us to evaluate the time efficiency of different authentication processes between the groups.
- **Time-Based Analysis**: With the `timestamp` field, time-based trends such as peak login times or daily activity patterns can be studied.

These files are intended to facilitate data analysis and comparison between the two groups, supporting conclusions about user satisfaction and the effectiveness of the changes implemented in the experimental group. The data can be used for further statistical analysis, visualization, or reporting.

Feel free to explore the CSV files to gain deeper insights into the study's findings and the differences between the control and experimental groups.


