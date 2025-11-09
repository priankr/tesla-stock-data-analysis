# Tesla Stock Price Data Analysis: AI-Assisted Workflow

---

## Context

Investors often use a company’s financial performance to evaluate investment decisions. The average individual investor does not have access to sophisticated tools to evaluate stock performance and understand the implications of different trends. This project explores how AI can be applied to analyze and contextualize stock performance, helping us understand how a company has been doing, so they can make informed investment decisions. As an example, we analyze the Tesla stock (TSLA) during a 4-year period (2021-2024) to evaluate and understand the trends leading up to December 2024, when the stock price reached an all-time peak.

You can find more details on this project [here](https://www.priankr.com/post/tesla-stock-price-data-analysis).

### Overview

This project evaluates different AI-assisted methodologies for improving stock performance analysis insights. The objective is to identify reproducible workflows that investors and analysts can leverage to extract deeper, more actionable insights with contextual market information.

### Core Question

**How can AI improve the quality of insights generated from stock performance data analysis?**

The project compares four approaches:

- **Enhanced Analysis**: AI reviews existing analysis in R, replicates it in Python, and draws new conclusions
- **Automated Analysis (Claude)**: AI conducts an independed analysis with complete freedom and contextualizes trends using news sources
- **Automated Analysis (Perplexity)**: AI conducts an independed analysis with web and financial search capabilities
- **Automated Analysis (Perplexity Research)**: AI conducts an independed analysis with deep research capabilities

---

## Dataset Information

**Source**: [NASDAQ Historical Data](https://www.nasdaq.com/market-activity/stocks/tsla/historical)

**Description**: The dataset contains Tesla Inc. (TSLA) historical stock price data over 4 years as of October 15, 2021. It includes daily stock information with date, open/close prices, daily high/low values, and volume of shares traded.

---

## Project Files

### Input Files

| File | Description |
| --- | --- |
| Tesla Stock Data (CSV) | Historical stock price data from NASDAQ containing date, open/close prices, daily high/low, and trading volume over 4 years |
| `tesla_stock.Rmd` | Original R Markdown notebook with baseline data analysis, including methodology, visualizations, and initial insights on Tesla stock performance |

### Analysis Prompts

| File | Description |
| --- | --- |
| `tesla_stock_analysis_prompt_v1.txt` | Initial and optimized prompts for **Automated Analysis** (Perplexity and Perplexity Research) |
| `tesla_stock_analysis_prompt_v2.txt` | Initial and optimized prompts for **Enhanced Analysis** approach |
| `tesla_stock_analysis_prompt_v3.txt` | Initial and optimized prompts for **Automated Analysis** (Claude), including Python Notebook generation prompt |
| `tesla_stock_analysis_comparison_prompt.txt` | Initial and optimized prompts for comparing outputs across all four approaches |

### AI-Generated Data Analysis

| File | Description |
| --- | --- |
| `tesla_stock_enhanced.ipynb` | **Enhanced Analysis**: Jupyter Notebook with AI-assisted Python replication of R analysis with improved insights |
| `tesla_stock_claude.ipynb` | **Automated Analysis (Claude)**: Jupyter Notebook with AI-generated analysis including causal context and market insights |

### Generated Outputs

| File | Description |
| --- | --- |
| Enhanced Analysis Output (Markdown) | AI-generated insights from reviewing and enhancing the existing R analysis |
| Claude Analysis Output (Markdown) | Comprehensive analysis with causal quantification, catalyst weighting, and investment insights |
| Perplexity Analysis Output (Markdown) | Analysis emphasizing volume-based technical context and contextual event timing |
| Perplexity Research Output (Markdown) | Detailed research report with extensive event documentation and regulatory precision |
| `tesla_stock_analysis_comparison.md` | Comparative analysis evaluating the quality, depth, and uniqueness of insights across all four approaches |

---

## Workflow

You can find a detailed version of this workflow [here](https://www.priankr.com/post/tesla-stock-price-data-analysis). This is just an overview of the process.

This project implements a systematic workflow to evaluate four AI-assisted stock analysis approaches. Each approach produces unique insights that are then compared to identify optimal use cases.

1. **Enhanced Analysis:** Review existing R analysis and replicate in Python with new insights
2. **Automated Analysis (Claude):** Conduct fresh analysis with causal context from news sources
3. **Automated Analysis (Perplexity):** Conduct fresh analysis with web and financial search
4. **Automated Analysis (Perplexity Research):** Conduct deep research with extensive documentation
5. **Comparative Analysis:** Evaluate quality, depth, and uniqueness of insights across all approaches
6. **Identify Optimal Use Cases:** Determine which approach works best for different investment scenarios

### Key Findings

**Enhanced Analysis** uncovered deep structural and technical patterns (volatility regime persistence, zero-false-signal moving averages) but lacked contextual and causal interpretation from external news sources.

**Automated Analysis (Claude)** delivered the most actionable and causally quantified insights, balancing catalyst weighting with recurring behavioral patterns and providing forward-looking sustainability warnings—optimal for real-time investment decision-making.

**Automated Analysis (Perplexity)** offered strong clarity and volume-based technical context, excellent for validating intraday dynamics and market event timing, though with limited causation quantification.

**Automated Analysis (Perplexity Research)** provided unmatched depth and event precision with extensive source documentation and regulatory detail, ideal for comprehensive due diligence though offering minimal synthesis for immediate investment action.

---

## Related Resources

- [Tesla Stock Price Data Analysis](https://www.priankr.com/post/tesla-stock-price-data-analysis) — Creating an enhanced AI-assisted workflow to examine Tesla Inc. (TSLA) stock price performance over a 4-year period
- [Meta Prompting Guide](https://www.priankr.com/post/how-to-optimize-prompts-guide-to-meta-prompting) — Learn how to optimize prompts using meta-prompting techniques

---