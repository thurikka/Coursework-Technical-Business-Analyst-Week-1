# JTBD and Prioritisation 

## Evidence table

| Stakeholder | Quote or observation | Theme | Business impact | Confidence |
|---|---|---|---|---|
| Head of Debt Recovery Operations, Finance Business Partner, Product Manager, Finance Analyst,Service Design Lead,Operations Analyst,Collections Agent | Agents spend too much time proving whether work already happened before they can act/ take the next action. | Fragmented systems | Reduces operational control, increases costs, risks revenue, affects delivery, adoption, and customer experience | High |
|Service Design|Customers need a simple route to understand balance and next action without calling first|Customer friction|Affects customer experience|Medium|
|Frontline Agents|Customers often repeat information because different records show different last-contact details|Customer friction|Affects customer experience|Medium|
|Operations Analyst, Collections Agent|Customers should be able to understand what they owe without calling first.|Customer friction|Increases costs, risks adoption|Medium|
|Finance Business Partner|Delayed next actions are contributing to avoidable revenue loss|Missed follow-ups|Risks revenue|Medium|
|Product Manager|I need a Phase 1 that can be built without pretending we are replacing the core collections platform immediately|Automation risks|Affects delivery|High|
|Finance Business Partner|I need assumptions that leadership can challenge without the whole case falling apart| Data confidence| Affects governance and finance|High|
|Senior Collections Team Leader| If the portal sends messy cases back to my team with no context| Automation risks| Agents will reject it| High
|Collections Agent, Service Design Lead, Service Design Lead, Compliance Liaison, Operations Analyst|If unsupported cases come back with no context, agents will reject the portal.|Automation risks|Reduces operational control, affects delivery, adoption, and customer experience|High|
|Collections Agent, Compliance Liaison, Finance Analyst|Leadership will challenge every assumption in the value case.|Data confidence| Reduces operational control, affects delivery, and customer experience| High
|Service Design Lead, Collections Agent, Operations Analyst, Senior Collections Team Leader| Managers need a clear view of whether self-service actually reduces workload.| Visibility|Reduces operational control, increases costs, risks revenue, affects delivery, adoption|High
|Senior Collections Team Leader|Managers need to see whether self-service is actually removing work or only moving it around|Visibility|Reduces operational control|High
|Frontline Agents| Promise-to-pay commitments are easy to lose when spreadsheets and notes are out of sync| Fragmented systems|Reduces control and affects customer outcomes|Medium|
|Risk and Compliance, Finance Analyst, Operations Analyst|Some cases must remain agent-led because risk or specialist review rules (still) apply|Automation risks|Reduces operational control, increases risk, raises costs, and affects delivery|High
|Head of Debt Recovery Operations, Compliance Liaison, Service Design Lead, Collections Agent|Straightforward accounts are not being handled fast enough because queues and manual tracking are mixed together/Straightforward cases are delayed because manual queues and trackers do not agree.|Fragmented systems|Risks revenue, increases costs, affects delivery, and adoption.|High
|Product Manager|Vague requirements will slow engineering down more than a smaller but clearer scope|Automation risks|Affects delivery|High


## JTBD statements

### Customer

- When I have an outstanding balance, I want to clearly understand what I owe and my options so that I can act without contacting support.
- When I’m contacted about a debt, I want to avoid repeating information so that the process feels smooth and not frustrating.

### Collections Agent

- When I pick up an account, I want to quickly understand its status and history so that I can take the correct next action.
- When managing multiple accounts, I want to know which cases need attention first so that I can prioritise effectively.

### Operations Manager

- When reviewing performance, I want visibility of self-service and agent work so that I can manage workload effectively.
- When overseeing operations, I want consistent follow-ups so that recovery opportunities are not missed.

### Finance Partner

- When reviewing the value case, I want confidence in assumptions and data so that I can support decisions.
- When assessing performance, I want to understand drivers of revenue loss so that we prioritise the right improvements.

## JTBD table

| JTBD ID | Actor | Statement | Evidence link | Portal relevance | Priority |
|---|---|---|---|---|---|
| JTBD-01 |Customer| When I have an outstanding balance, I want to clearly understand what I owe and my options so that I can act without contacting support.| Customer friction: need clear balance & next steps (Service Design, Operations Analyst, Collections Agent)| High – directly solved by the self-service portal | High|
| JTBD-02 | Customer| When contacted about a debt, I want to avoid repeating information so that the process feels smooth.| Fragmented systems: customers repeat info due to inconsistent records (Frontline Agents)| Medium – can reduce repeated contact| Medium   |
| JTBD-03 | Collections Agent  | When I pick up an account, I want to quickly understand its status and history so that I can take the correct next action.| Fragmented systems: time spent reconciling past work (Collections Agent, Operations Analyst, Head of Debt Recovery)| Low – portal doesn’t directly support this workflow| High|
| JTBD-04 | Collections Agent  | When managing multiple accounts, I want to know which cases need attention first so that I can prioritise effectively.| Missed follow-ups: unclear prioritisation causes delays (Collections Agent, Finance Analyst, Operations Analyst)| Medium – portal may reduce volume of simple cases but not solve prioritisation fully | High|
| JTBD-05 | Operations Manager | When reviewing performance, I want visibility of self-service and agent work so that I can manage workload effectively.                 | Visibility: lack of clarity on workload and self-service impact (Senior Collections Team Leader, Operations Analyst)| High – portal creates need for this visibility | Medium |
| JTBD-06 | Operations Manager | When overseeing operations, I want confidence that follow-ups are completed consistently so that recovery opportunities are not missed. | Missed follow-ups + revenue loss (Finance Analyst, Operations Analyst)| Medium – portal may automate or support some follow-ups| High|
| JTBD-07 | Finance Partner    | When reviewing possible investments, I want confidence that the assumptions and data are accurate so that I can make informed decisions.| Data confidence: assumptions challenged by leadership (Finance Business Partner)| Low – not portal-related | High|
| JTBD-08 | Finance Partner| When assessing performance, I want to understand drivers of revenue loss so that we prioritise improvements.| Revenue + missed follow-ups: delays contributing to loss (Finance Partner, Operations Analyst) | Medium – portal may impact recovery rates| High|


## Top 3 justification
1. JTBD-01 – Customer balance & options

    - Why it matters now: High customer friction - repeated calls slow recovery and increase agent workload.
    - Evidence: Multiple quotes: “Customers need a simple route to understand balance and next action without calling first” (Service Design, Operations Analyst, Collections Agent)
    - Phase 1 influence: High relevance to self-service portal, reducing repeated contact, freeing agent time, and improving recovery speed.

2. JTBD-06 – Confidence follow-ups completed

    - Why it matters now: Missed follow-ups directly reduce recovery performance and revenue.
    - Evidence: “Delayed next actions contribute to avoidable revenue loss” (Finance Business Partner) - “Managers need visibility of self-service impact” (Senior Collections Team Leader)
    - Phase 1 influence: Introduce automation or tracking dashboards to ensure follow-ups are reliably completed - impacts workflow design and ROI calculation.

3. JTBD-03 – Agent understanding account status & history

    - Why it matters now: Agents waste significant time reconciling past work, leading to inefficiency and potential errors.
    - Evidence: Multiple quotes:“Agents spend excessive time reconciling past work” (Head of Debt Recovery Operations, Collections Agent, Operations Analyst)
    - Phase 1 influence: Could shape portal features or internal tooling for faster account overview and reduce duplicate effort.

