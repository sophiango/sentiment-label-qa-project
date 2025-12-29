# Sentiment Label QA — Quality Review Report

## Objective
The goal of this project is to review AI-generated sentiment labels
(Positive / Negative) applied to viewers' reviews for movies,
and identify labeling accuracy issues, ambiguity, and risk.

## Dataset
10 IMDB viewer reviews (synthetic dataset)

AI Labels:
- Positive
- Negative

I manually reviewed each item and marked:
- Correct / Incorrect
- Correct label if wrong
- Severity of the issue (Low/High)
- Notes explaining my reasoning

## Results
- Total samples reviewed: 10
- Incorrect labels: 4
- Accuracy: 60%

## Common Issues Observed
1. Negative review labeled Positive
2. Postitive review labeled Negative

## Risk Assessment
High-severity issues:
- Rows 3, 5, 10:
  Positive review must be captured correctly.
- Row 8:
  Negative review should be captured correctly.

## Recommendations
- Add clearer rules for:
  - Mixed sentiment handling
  - Short ambiguous text
  - Negative experience priority weighting
- Consider confidence scoring before assigning sentiment
- Flag ambiguous text for manual review

## Reflection
This project demonstrates my ability to:
- Consistently review AI-labeled data
- Identify labeling quality issues
- Document ambiguity and risk clearly
- Write structured QA reports

