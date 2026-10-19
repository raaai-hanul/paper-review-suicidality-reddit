# Paper Review: Detection of Suicidality Among Opioid Users on Reddit

**Context:** ISP560 Machine Learning (UiTM) | **Paper:** Yao et al. (2020), Journal of Medical Internet Research

A critical review of a machine learning study that classifies Reddit posts, using subreddit membership as natural labels.

## What I Evaluated
- Problem, data (51,366 and 59,940 posts across two cases) and methods (Logistic Regression, Random Forest, SVM, FastText, RNN, attention-based BiRNN, CNN, AdaBoost ensemble)
- **Strengths:** creative use of subreddits as labels, ensemble robust to class imbalance (80 to 94% accuracy), clinically relevant co-occurring terms
- **Weaknesses:** the second model failed (23 to 41% accuracy on the positive class), only one year of data, no framework for intervention

## Why It Is Here
It shows I can read a research paper critically, judge evaluation choices such as class imbalance, and communicate findings visually (see the infographic).

## Files
- `paper_review.pdf`
- `infographic.png`
