# GPT-4 Portfolio Experiment
- Please feel free to make changes and run the code in [Google Colab](https://colab.research.google.com/github/spehl-max/GPT4_Portfolio_Experiment/blob/main/GPT_4_Portfolio_Experiment.ipynb)
## Overview
This project explores the effectiveness of using GPT-4, a large language model, to construct useful investment portfolios. The experiment involved creating portfolios with different strategies: a negative control (expected to underperform the S&P 500), a control (expected to match the S&P 500), and an experimental treatment with additional information provided to GPT-4.

## Methodology
- **Portfolio Construction**: Utilizing the OpenAI package and Python's Pandas library, three distinct portfolios were created based on GPT-4's recommendations.
- **Experiment Design**: 
  - *Negative Control*: A portfolio designed to underperform the S&P 500.
  - *Control*: A portfolio expected to match the S&P 500 performance.
  - *Experimental Treatment*: An informed portfolio with additional, pre-April 2023 data fed to GPT-4.

## Results
Surprisingly, all three portfolios outperformed the S&P 500 by approximately 20%. This outcome suggests that GPT-4's stock picks were influenced more by prominence in its training data rather than genuine financial insight.

## Conclusion
The experiment raises questions about the reliability of large language models like GPT-4 in financial advising contexts. It is recommended to exercise caution and not solely rely on LLMs for financial decisions.


*Note: This project is for experimental purposes and should not be considered financial advice.*
