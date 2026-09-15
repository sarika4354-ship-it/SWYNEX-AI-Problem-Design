# SWYNEX AI Problem Design

## Project Title
Student Performance Risk Classification Using AI

## 1. Problem Statement
Educational institutions need to identify students who may be academically at risk at an early stage. This project defines an AI-based classification problem that predicts whether a student is "At Risk" or "Not At Risk" using academic and engagement-related data.

## 2. Target Users
- Teachers
- Academic advisors
- Educational institutions

## 3. AI Use Case
This is a classification problem. The AI system classifies students into two categories:
- At Risk
- Not At Risk

## 4. Dataset
The dataset is a synthetic student performance dataset created for this project.

### Features
- Student_ID
- Study_Hours
- Attendance
- Previous_Mark
- Assignment_Score

### Target
- Result

## 5. Data Source
The dataset is a manually created synthetic dataset for educational and demonstration purposes. It does not contain real student personal information.

## 6. Constraints
- The dataset is small.
- Synthetic data may not represent real-world student behaviour completely.
- Student data should be handled with privacy and security considerations.
- Missing or inaccurate input data may affect classification performance.

## 7. Evaluation Approach
The classification system can be evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score

Recall is especially important because correctly identifying students who are "At Risk" can help teachers provide timely support.

## 8. Success Criteria
The AI solution will be considered successful if:
- It achieves approximately 80% or higher classification accuracy.
- It provides good recall for identifying "At Risk" students.
- The results are understandable and useful for academic support decisions.

## 9. Expected Outcome
The proposed AI system can help teachers and academic advisors identify students who may need additional academic support at an early stage.
