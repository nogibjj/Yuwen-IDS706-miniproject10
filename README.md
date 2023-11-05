### IDS-706 Miniproject# 10 by Yuwen Cai

[![cicd](https://github.com/nogibjj/Yuwen-IDS706-miniproject10/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-miniproject10/actions/workflows/cicd.yml)

---
**Dataset Source**
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv

---

**Summary**

This project serves to utilize PySpark for data processing on a substantial dataset. The main objectives are to incorporate a Spark SQL query and execute a data transformation. I use the iris dataset to perform these operations.

---
**Project Structure**

- **`lib.py(mylib/lib.py)`**:
  - Functions to extract online datasets and transform datasets into Pyspark SQL and perform queries.

- **`Makefile`**:
  - `Install`: Install dependencies via `pip install -r requirements.txt`
  - `Test`: Run all tests (test_*.py)
  - `Format`: Format code with Python black
  - `Lint`: Lint code with Ruff

- **`main.py(main.py)`**:
  - Use cases for the lib.py script loading dataset from URL and performing the transformation.

- **`test_main.py(test_main.py)`**:
  - Test cases for the main.py script.

---

**Getting Started**

This section is included in ```pyspark_output.md```

### Pandas Descriptive Statistics
![](/output/description.png)

### Pass local make test
![](/output/local_test.png)

### Pass GitHub Actions
![](/output/github_actions.png)


---

**Run**

### Some Makefile Commands
```command line
make install
make format
make lint
make test
make all
```


