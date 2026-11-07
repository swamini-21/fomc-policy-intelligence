# Project log

Phase-by-phase build history for this project. For the overview and results, see the [main README](../README.md).


- Phase 1: notebook and data audit completed in [`docs/audit_report.md`](audit_report.md).
- Phase 2: architecture and foundational scaffold completed in [`docs/architecture.md`](architecture.md).
- Phase 3: local document and VIX ingestion, validation, identity, and safe preprocessing implemented in [`docs/data_pipeline.md`](data_pipeline.md).
- Phase 4: completed as a measured baseline with tokenizer-safe inference, aggregation,
  policy rules, topic interfaces, reviewed annotations, and a reproducible evaluation
  command. See
  [`docs/nlp_pipeline.md`](nlp_pipeline.md) and
  [`docs/model_evaluation.md`](model_evaluation.md). Initial baseline results and
  limitations are reported in
  [`docs/model_evaluation_results.md`](model_evaluation_results.md).
- Phase 5: the expert-labelled domain-classifier path and structured LLM layer are
  complete. Gemini remains experimental after bounded evaluation; the local
  expert-supervised classifier is the primary stance measure.
- Phase 6: statement-only event construction, S&P 500 and Treasury extensions, and
  the final explanatory statistical workflow are complete. No language block survives
  multiplicity correction and crisis exclusion.
- The current research specification replaces the broad NLP block with a prespecified
  hierarchy: market controls, expert-supervised FOMC stance, secondary sentiment, and
  exploratory fear. It adds descriptive tests, rank and linear correlations,
  stance-group comparisons, robust inference, Holm correction, influence diagnostics,
  and crisis sensitivity. Results are associations rather than predictions or causal
  effects. See [`docs/research_analysis.md`](research_analysis.md).
- Reproducible S&P 500 and Treasury-yield downloads now extend the study beyond VIX.
  The richer controls attenuate the earlier one-day VIX result, and no stance,
  sentiment, or emotion block survives multiplicity correction and crisis exclusion.
  See [`docs/market_data.md`](market_data.md).
- Phase 7: an interactive Streamlit research explorer now presents cached statements,
  policy trends, cross-market reactions, robust regression results, and limitations
  without API access or predictive claims. See
  [`docs/streamlit_app.md`](streamlit_app.md).
- Phase 8: 80 automated tests cover the research modules, cache failure modes, and all
  dashboard views.
- Phase 9: consolidated methodology, clean-environment verification, exact runbook,
  and repository/security review are complete. See
  [`docs/methodology.md`](methodology.md) and
  [`docs/final_implementation_report.md`](final_implementation_report.md).
- Expert-supervised policy stance: the pinned Georgia Tech FOMC dataset now trains a
  local RoBERTa-base classifier, which is evaluated on its untouched external test
  split and applied sentence by sentence to all 295 market-eligible statements. See
  [`docs/domain_policy_results.md`](domain_policy_results.md).
- The structured policy-intelligence contract, evidence audit, provenance, cache, and
  Gemini live provider are implemented. The mock remains the offline default. Provider
  evaluation found that Gemini should remain an experimental enrichment layer rather
  than replace the local stance classifier. See
  [`docs/llm_policy_intelligence.md`](llm_policy_intelligence.md) and
  [`docs/gemini_bounded_evaluation.md`](gemini_bounded_evaluation.md).

