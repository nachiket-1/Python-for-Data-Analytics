<div align="center">

<img src="images/banner.png" alt="Python for Data Analysis" width="100%">

<br>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Runs%20on-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20progress-6a4c9c)

</div>

<br>

## What this is

A business has questions. Which product earns the most? Which branch is slow? Which customers might leave? Python can answer all of them, and this repo is where I learn how.

Every notebook here teaches one small piece of Python, and every example comes from a business situation instead of a textbook one. You will see prices, profits, sales lists and customer decisions, not `foo` and `bar`.

If you have never written a line of code, you can still follow along. Each notebook starts simple and builds slowly.

<br>

## A taste of it

Here is the kind of thing you will be writing by notebook 4. A business wants to know if it made a profit.

```python
profit = 15000

if profit > 0:
    print("Positive profit")
else:
    print("No positive profit")
```

Four lines, one real decision. That is the whole idea of the repo.

<br>

## The big picture

Data analytics is not one step, it is a chain. Raw data gets collected, tidied up, studied, drawn as charts, and only then does it turn into a decision. Python helps at every link.

<div align="center">
<img src="images/analytics_process.png" alt="The data analytics process" width="95%">
</div>

<br>

## Why Python

It reads almost like English, it handles large business datasets without complaint, and it has a library for nearly everything. The picture below shows how the ecosystem is layered. At the centre is the language itself, then the core tools like NumPy, pandas and matplotlib, then specialised ones, then libraries built for particular fields.

<div align="center">
<img src="images/python_ecosystem.png" alt="The Python ecosystem" width="85%">
</div>

<br>

## Where it shows up in a business

The same few skills apply whether you work in sales, HR, customer service or operations.

<div align="center">
<img src="images/python_business_areas.png" alt="Python in sales, HR, customer and operations analytics" width="85%">
</div>

<br>

## From numbers to a decision

Take three products and a few numbers. With a handful of lines you can work out revenue, profit and margin, then decide which one deserves more promotion.

| Product | Units Sold | Selling Price | Cost | Profit | Margin |
|---|---|---|---|---|---|
| Product A | 120 | 500 | 350 | 18,000 | 30.0% |
| Product B | 80 | 700 | 500 | 16,000 | 28.6% |
| Product C | 150 | 300 | 220 | 12,000 | 26.7% |

<div align="center">
<img src="images/data_to_decisions.png" alt="Revenue, profit and margin by product" width="95%">
</div>

Product A earns the most profit and has the best margin, so it is the one to push. That small piece of reasoning is what analytics is really about.

<br>

## The notebooks

Go in order. Each one uses ideas from the one before it.

| # | Notebook | What you will learn | Open |
|:-:|---|---|:-:|
| 0 | `0_Analytics_Basics.ipynb` | What analytics is, why Python, and where it fits in a business | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/0_Analytics_Basics.ipynb) |
| 1 | `1_Variables.ipynb` | Storing business values like price, units and profit | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/1_Variables.ipynb) |
| 2 | `2_Operators_and_Expressions.ipynb` | Calculating revenue, cost, profit and margin | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/2_Operators_and_Expressions.ipynb) |
| 3 | `3_Lists.ipynb` | Holding many values together, like monthly sales figures | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/3_Lists.ipynb) |
| 4 | `4_If_Else_Statements.ipynb` | Making decisions in code, like checking if profit is positive | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/4_If_Else_Statements.ipynb) |

<br>

## Where this is heading

This repo is still growing. Here is the road ahead.

| Stage | Topic | Status |
|---|---|---|
| Foundations | Python basics, variables, operators, lists, if else | ✅ Done |
| Working with data | Business datasets, cleaning and preparation | 🚧 Next |
| Seeing the data | Data visualization, descriptive analytics | ⏳ Planned |
| Proving things | Hypothesis testing | ⏳ Planned |
| Predicting | Regression, classification models | ⏳ Planned |
| Doing it well | Model evaluation and improvement | ⏳ Planned |

<br>

## Running it yourself

The easiest way is Google Colab. Click any **Open in Colab** badge in the table above and the notebook runs in your browser, with nothing to install.

If you prefer your own machine:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
pip install jupyter
jupyter notebook
```

<br>

## How the repo is laid out

```
.
├── 0_Analytics_Basics.ipynb
├── 1_Variables.ipynb
├── 2_Operators_and_Expressions.ipynb
├── 3_Lists.ipynb
├── 4_If_Else_Statements.ipynb
├── images/
└── README.md
```

<br>

<div align="center">

Found a mistake or have a better business example? Open an issue, I would love to hear it.

If this helped you, a ⭐ on the repo goes a long way.

</div>
