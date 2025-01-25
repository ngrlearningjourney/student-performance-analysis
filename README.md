# 📊 Data Analysis Portfolio: Student Performance

Welcome to my data analysis portfolio! This project dives into student performance data, providing valuable insights into the factors that influence academic success. Here's an overview of the process, analysis, and insights.

---

## 📥 Data Overview

The dataset, sourced from Kaggle, contains information about various factors that could impact a student's academic performance. The data is in CSV format and includes the following key columns:

| **Feature**                 | **Description**                                                                           |
|-----------------------------|-------------------------------------------------------------------------------------------|
| `Hours_Studied`             | Number of hours spent studying per week.                                                 |
| `Attendance`                | Percentage of classes attended.                                                          |
| `Parental_Involvement`      | Level of parental involvement in the student's education (`Low`, `Medium`, `High`).       |
| `Access_to_Resources`       | Availability of educational resources (`Low`, `Medium`, `High`).                         |
| `Extracurricular_Activities`| Participation in extracurricular activities (`Yes`, `No`).                               |
| `Sleep_Hours`               | Average number of hours of sleep per night.                                              |
| `Previous_Scores`           | Scores from previous exams.                                                              |
| `Motivation_Level`          | Student's level of motivation (`Low`, `Medium`, `High`).                                 |
| `Internet_Access`           | Availability of internet access (`Yes`, `No`).                                           |
| `Tutoring_Sessions`         | Number of tutoring sessions attended per month.                                          |
| `Family_Income`             | Family income level (`Low`, `Medium`, `High`).                                           |
| `Teacher_Quality`           | Quality of the teachers (`Low`, `Medium`, `High`).                                       |
| `School_Type`               | Type of school attended (`Public`, `Private`).                                           |
| `Peer_Influence`            | Influence of peers on academic performance (`Positive`, `Neutral`, `Negative`).          |
| `Physical_Activity`         | Average number of hours of physical activity per week.                                   |
| `Learning_Disabilities`     | Presence of learning disabilities (`Yes`, `No`).                                         |
| `Parental_Education_Level`  | Highest education level of parents (`High School`, `College`, `Postgraduate`).           |
| `Distance_from_Home`        | Distance from home to school (`Near`, `Moderate`, `Far`).                                |
| `Gender`                    | Gender of the student (`Male`, `Female`).                                                |
| `Exam_Score`                | Final exam score.                                                                        |

---

## 🛠️ Data Cleaning and Preparation

### Key Techniques Applied:
1. **Duplicate Handling**: Removed duplicate rows to ensure data integrity.
2. **Missing Values**: Imputed missing values using appropriate methods based on column types.
3. **Data Type Corrections**: Ensured all columns have consistent and correct data types.
4. **Outlier Detection**: Identified and managed outliers to prevent skewed analysis.
5. **Misspellings**: Corrected spelling errors in categorical variables.

---

## 🔍 Exploratory Data Analysis (EDA)

In this phase, I conducted an in-depth analysis of each column in the dataset to uncover meaningful patterns and insights aimed at improving student exam scores. The analysis also included calculating correlations between various factors and exam performance to identify the most impactful predictors.

#### Exam Score Correlation Analysis
To determine the factors most strongly associated with exam scores, I used multiple correlation methods: **Pearson**, **Spearman**, and **Point Biserial**.

- **Highest Correlation: Percentage of Classes Attended**  
  - Correlation Coefficient: **0.58**  
  - The percentage of classes attended shows the strongest positive correlation with exam scores. This result highlights that students who attend classes more regularly are more likely to perform better on exams. This underscores the importance of maintaining consistent attendance for academic success.

- **Second Highest Correlation: Hours Spent Studying per Week**  
  - Correlation Coefficient: **0.43**  
  - The number of hours spent studying each week has a moderate positive correlation with exam scores. While this relationship is not as strong as class attendance, it emphasizes that consistent study habits also play a significant role in improving performance.

- **Summary of Correlation Results**  
  - Both factors show positive correlations (**0.58** and **0.43**), indicating that as class attendance and weekly study hours increase, exam scores tend to improve.  
  - These results reveal a moderate positive relationship, suggesting the importance of attendance and study habits while acknowledging that other variables, such as motivation, access to resources, and extracurricular involvement, may also significantly impact performance.

---

## ❓ Key Questions Explored

Here are some of the critical questions I explored to uncover insights:

1. **Which factor has the strongest correlation with exam scores?**  
   I used summary tables to identify the strongest predictor of exam performance.

2. **How do hours studied compare between students in private vs. public schools?**  
   Comparative tables showed differences in average, maximum, and minimum hours studied.

3. **Do extracurricular activities affect exam scores?**  
   I compared the percentage of students scoring above 75 based on participation.

4. **How does tutoring impact high achievers?**  
   Tables illustrated the number of tutoring sessions attended by students with scores > 90.

5. **Does teacher quality affect exam scores?**  
   Exam scores were grouped and summarized by teacher quality (`High`, `Medium`, `Low`).

---

### Insights

#### 🌟 Class Attendance and Study Habits
- **Class Attendance:** Students who attend more classes tend to score higher on exams! There’s a strong positive correlation (0.58) between attendance and exam scores, showing how crucial regular attendance is for success.  
- **Study Hours:** The number of hours spent studying per week also matters, with a moderate positive correlation (0.43) to exam scores. Consistent study time plays an important role in improving performance.

#### 🏫 School Type and Study Hours
- Interestingly, students from private and public schools have similar study habits. Both report a range of study hours between 4 and 36 per week.  
- This suggests that where students study doesn’t matter as much as how much effort they put into it. Success is within reach for everyone who puts in the time!

#### 👩‍🏫 Teacher Quality and Exam Performance
- Surprisingly, teacher quality doesn’t seem to drastically impact top scores. Students with high, medium, and low teacher quality all achieve a maximum score of 100.  
- Average scores across these categories are very close (around 66-67), so while teacher quality might not be a game-changer for extreme performance, it could still shape the overall learning experience.

#### 🏅 Extracurricular Activities and Exam Performance
- Participating in extracurricular activities might give students an edge! Among students who scored above 75, 87 were involved in activities compared to only 37 non-participants.  
- While it’s not a guaranteed path to higher grades, being involved in activities can help build skills like time management, teamwork, and leadership that contribute to success.

#### 📚 Tutoring Sessions and High Scores
- Many top scorers (above 90) attend tutoring sessions at least once a month. Regular tutoring seems to help students reach their goals, even with just a monthly session.  
- That said, other factors like study habits, teacher support, and extracurricular involvement also contribute to success.

---

### Recommendations

#### 🏫 Encourage Regular Class Attendance
Attendance matters! Schools should find creative ways to motivate students to come to class more often. Interactive lessons, fun activities, or even small rewards for good attendance can make a big difference.

#### 📖 Promote Consistent Study Habits
Good study habits are key! Schools and parents should encourage students to set aside regular time for studying. Even small but consistent efforts can lead to big improvements over time.

#### ✏️ Invest in Teacher Development
Although teacher quality doesn’t directly impact extreme scores, it can play a big role in helping students in the mid-range. Providing teachers with professional development opportunities, workshops, or new teaching tools could lead to better engagement and learning outcomes.

#### 🎨 Support Extracurricular Activities
Extracurricular activities are not just fun—they help students grow! Schools should offer more options and encourage students to get involved. Balancing academics with activities helps students develop life skills that lead to both academic and personal success.

#### 💡 Make Tutoring Accessible
Tutoring works! Schools should consider making tutoring sessions more available, especially for students struggling in specific areas. Even a monthly session can be incredibly beneficial.

---

## 💡 Tools and Technologies
- **Python**: Data wrangling and analysis.
- **Pandas**: Data manipulation.
- **Jupyter Notebook**: Environment for analysis and reporting.
- **GitHub**: Version control and project management.
