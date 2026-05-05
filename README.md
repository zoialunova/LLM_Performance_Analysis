# LLM_Performance_Analysis
Exploratory data analysis of large language models evaluated  across 6 benchmarks: IFEval, BBH, MATH Lvl 5, GPQA, MUSR, MMLU-PRO.

## What's inside

- **Size vs Performance** — do larger models always score higher?
- **Efficiency** — how much performance do you get per billion parameters?
- **Merged models** — does merging actually improve quality?
- **Popularity vs Quality** — do more liked models perform better?
- **Architecture comparison** — Llama, Qwen2, Mistral, Gemma2 head-to-head
- **Chat template effect** — does instruction tuning help across all benchmarks?

## Key Findings

- Bigger models score higher, but with diminishing returns
- Medium models offer the best performance-to-cost trade-off
- Popularity has almost no correlation with quality (R² = 0.018)
- Llama leads in logic and instruction following, Qwen2 leads in math
- Chat template gives +17 points on IFEval, but hurts on reasoning tasks

- ## Dataset

[Open LLM Leaderboard on Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/elvisbui/open-llm-leaderboard-evaluations-2026/data))
