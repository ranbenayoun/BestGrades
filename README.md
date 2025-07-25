# BestGrades

This project pulls course statistics from Michael Maltsev’s [CheeseFork](https://cheesefork.cf/) and extracts key insights for any Technion course.
The presentation can be found in [Youtube Presentation](https://youtu.be/uwcc7UkbG20)

## 📊 What this code does:

- Calculates the **average median grade** for each course
- Identifies the **maximum grade** recorded for each course

The script processes **all MALAG courses for 2025**, including sports courses, so every Technion student can benefit from the insights.

While the main analysis focuses on **Biomedical Engineering** courses, the code supports any syllabus and can be adapted accordingly.

## Limitations

- The statistics are based only on **available histograms**. Courses with no histograms (typically those with under 10 students or no shared data) are **not included** in the analysis.
- **Course numbers change occasionally**, which can result in data loss or duplication.
- In **2024**, the Technion changed course numbers from 6 digits to 7 or 8 digits. This created inconsistencies in the dataset.

## 📈 Visualizations

### Average Median Grades – BME Mandatory Courses  
![Average Median Grades](https://github.com/ranbenayoun/BestGrades/blob/main/Average%20Median%20Grades%20for%20BME%20Mandatory%20Courses.png?raw=true)

### Maximum Grades – BME  
![Max Grades in BME](https://github.com/ranbenayoun/BestGrades/blob/main/MaxGrades.png?raw=true)

### MALAG Course Medians Over Time  
![Malag grades](https://github.com/ranbenayoun/BestGrades/blob/main/Malag_courses_medians_over_time.png?raw=true)
