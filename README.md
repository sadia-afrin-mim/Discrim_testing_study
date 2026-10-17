Discrimination Testing Education

Course materials for a study on teaching software fairness. Students learn to detect discriminatory behavior in software using combinatorial testing with the ACTS tool.

---

 Components

1.Exercise Description — Assignment PDFs for both groups. The control group tests using traditional online resource; the experiment group tests using traditional online resource and LLM.

2.Programming Artifact — A Python-based discrimination testing framework. It uses ACTS to generate t=2-way combinations of protected attributes (gender, race, income), runs them against the target software, and measures discrimination via Statistical Parity Difference.

3.Survey Forms — Pre and post surveys for both groups, used to measure change in student confidence around fairness concepts.
4.Learning Content - Introductory Lecture and Related Research Article

---

Running the artifact

Requires Python 3, Java, and `pandas` / `scikit-learn`.

```bash
# Rule-based evaluation 
python run_loan_fairness.py

# ML model evaluation
python run_lr_fairness.py
```

ACTS must be present in the `ACTS3/` directory. Results are saved to `Data/tWay_Abstract_TC/`.

---


