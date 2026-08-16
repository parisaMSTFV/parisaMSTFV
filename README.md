<p align="center">
  <img src="./assets/profile-banner.svg" alt="Parisa Mostafavi — Customer Analytics and Decision Science" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/parisa-mostafavi/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:parisamostafavi23@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-334155?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## Customer analytics and decision science that ends in an action

I am an analytics and customer insight leader with 7+ years of experience across marketing analytics, customer strategy, planning, budgeting, and P&L in large-scale ecommerce.

I build decision systems for questions such as **who to retain, which intervention to use, which customers to invest in, where to allocate budget, and how to measure incremental value**. Python, SQL, machine learning, causal inference, forecasting, and optimization support the decision; they are not the endpoint.

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Target roles</strong><br />
      Decision Scientist · Customer Analytics · Data Scientist · Marketing Analytics
    </td>
    <td width="50%" valign="top">
      <strong>Delivery standard</strong><br />
      Business framing · Baselines · Holdouts · Uncertainty · Decision policy · Tests · CI
    </td>
  </tr>
</table>

## Start here

The portfolio separates three evidence levels: licensed external validation, validated supplied-input contracts, and controlled synthetic benchmarks. Each repository states which level supports each claim.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/customer-next-best-action-engine">Customer Next Best Action Engine</a></h3>
      <p><strong>Decision:</strong> Who should receive which action now—or no action—under budget, consent, contact-frequency, and channel constraints?</p>
      <p><strong>Evidence:</strong> Versioned upstream contracts plus a controlled benchmark. The policy created 15.4% more synthetic true incremental net value than the strongest non-oracle baseline, with zero constraint violations.</p>
      <p><code>Decision orchestration</code> <code>Optimization</code> <code>Uplift</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/customer-lifetime-value-decision-system">Customer Lifetime Value Decision System</a></h3>
      <p><strong>Decision:</strong> Which customers warrant scarce service capacity, and what investment ceiling is defensible?</p>
      <p><strong>External validation:</strong> On licensed UCI retail transactions, the model improved ranking and top-20% value capture, while the simple baseline retained better point accuracy. The mixed result is reported without cherry-picking.</p>
      <p><code>SQL</code> <code>Temporal ML</code> <code>Uncertainty</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/retention-treatment-uplift">Retention Treatment Uplift</a></h3>
      <p><strong>Decision:</strong> Who should receive a retention action when cost, budget, and capacity matter?</p>
      <p><strong>External validation:</strong> On the randomized Criteo benchmark, the targeted visit effect was 1.403% (95% CI 0.279% to 2.528%); improvement over random targeting at matched reach was 0.297% per eligible row.</p>
      <p><code>Causal ML</code> <code>AIPW</code> <code>Policy evaluation</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/marketing-experiment-incrementality">Marketing Experiment Incrementality</a></h3>
      <p><strong>Decision:</strong> Scale, redesign, or stop a campaign after reconciling causal effect and full cost?</p>
      <p><strong>Executed decision:</strong> <code>Redesign</code>. Estimated net incremental profit was -259, with a 95% interval from -13,226 to 12,709 synthetic currency units.</p>
      <p><code>Experimentation</code> <code>CUPED</code> <code>Economics</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/marketing-budget-allocation-optimizer">Marketing Budget Allocation</a></h3>
      <p><strong>Decision:</strong> How should a limited budget move across category-channel cells under diminishing returns and operating constraints?</p>
      <p><strong>Evidence:</strong> A validated weekly-response input contract plus a synthetic benchmark in which the optimized plan produced 10.2% more profit than the feasible historical mix.</p>
      <p><code>Response curves</code> <code>Linear programming</code> <code>Scenario planning</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/parisaMSTFV/ecommerce-demand-forecasting">Ecommerce Demand Forecasting</a></h3>
      <p><strong>Decision:</strong> How much category-level capacity should operations prepare over the next eight weeks?</p>
      <p><strong>Evidence:</strong> A guarded aggregate input path plus a synthetic benchmark with 4.9% untouched-holdout WAPE and 80.8% coverage for the nominal 80% interval.</p>
      <p><code>Forecasting</code> <code>Backtesting</code> <code>Capacity planning</code></p>
    </td>
  </tr>
</table>

## Supporting portfolio

| Decision area | Project | What it demonstrates |
|---|---|---|
| Customer strategy | [Customer Segmentation](https://github.com/parisaMSTFV/customer-segmentation-decision-system) | Stable assignments, definition fingerprints, holdout evaluation, and supplied features |
| Retention prioritization | [Personalized-Window Churn](https://github.com/parisaMSTFV/customer-churn-personalized-window) | Customer-specific timing, chronological evaluation, and validated transactions |
| Subscription economics | [Subscription Value & P&L](https://github.com/parisaMSTFV/subscription-value-pnl-analytics) | Portfolio P&L, renewal analysis, sensitivity, and executable SQL |
| Recommendation | [Next Purchase Recommendation](https://github.com/parisaMSTFV/next-purchase-recommendation) | Purchase cadence, category review queues, provenance, and future-row isolation |
| Operations risk | [Delivery Risk Decision System](https://github.com/parisaMSTFV/ecommerce-delivery-risk-decision-system) | Paired policy uncertainty and a documented shadow-test decision |
| Entity resolution | [Customer Relation Detection](https://github.com/parisaMSTFV/customer-relation-detection) | Graph linkage, deferred-edge audit, and component-explosion guardrails |
| Network analysis | [Community Detection](https://github.com/parisaMSTFV/community-detection) | Validated edge-list inputs, weighted graphs, and community diagnostics |
| Business governance | [Agentic Business Review](https://github.com/parisaMSTFV/agentic-business-review) | Supplied KPI contracts, deterministic review logic, and human approval states |

## Evidence discipline

- **External validation** means the workflow was executed on a named, licensed public dataset with provenance and an untouched evaluation boundary.
- **Supplied-input contract** means an external user can pass validated data through a documented schema; it is not evidence of performance on that user's data.
- **Synthetic benchmark** means the repository demonstrates mechanics and decision behavior under controlled assumptions, including simulation-only truth where explicitly labeled.

## How I work

- Start with the stakeholder decision, objective, KPI, action, and operating constraint.
- Compare against an understandable baseline and protect temporal or untouched holdouts.
- Separate prediction, causal impact, uncertainty, and business value so the claim matches the evidence.
- Translate model output into an explicit policy, including no-action cases and guardrails.
- Make provenance, limitations, tests, and CI part of the deliverable.

## Core toolkit

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-0F766E?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="Pytest" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=111827" alt="Power BI" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white" alt="Tableau" />
</p>

## Data boundary

No employer data, schema, query, dashboard, business rule, secret, or internal threshold is published. Synthetic evidence is labeled as synthetic. Licensed public validation states its source, license, checksum or retrieval controls, and remaining limits. Production use would require governed data, privacy review, monitoring, and business validation.
