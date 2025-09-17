# A/B Testing: New Landing Page vs Control

This project analyzes an e-commerce experiment to check whether a new landing page improves the conversion rate.

## Dataset

| Column      | Description                                  |
| ----------- | -------------------------------------------- |
| `timestamp` | Date and time of the visit                   |
| `group`     | `control` or `treatment`                     |
| `converted` | 1 if user purchased / signed up, 0 otherwise |

## Steps

1. Load & clean the dataset
2. Explore conversions by group
3. Run a statistical test (two-proportion z-test)
4. Report findings
