# Project Overview Form: draft answers

Microsoft AI Economy Institute, Cohort 4 open call. Due **Dec 31, 2026, 6 pm Pacific**. DRAFT of 2026-11-22, not submitted.

This plan follows the list of contents on the public call page: research question, objectives, goals and milestones; alignment with the themes, methodology, anticipated outcomes and impact, and potential risks; and up to three target journals.

Square brackets mark decisions that are still open.

---

## Title

**The Shape of the First Rung: How AI Changes What Entry-Level Jobs Ask People to Do**

## Principal investigator(s)

Nik Bear Brown, PhD, Associate Teaching Professor, College of Engineering, Northeastern University.
[DECIDE: a second PI. The call allows two and prefers interdisciplinary teams. An economist or management scholar would cover the labor-market side.]

## Themes

Primary: **Building Expertise and the First Rung.**
Secondary: **Designing for Augmentation and Innovation: Tasks, Skills, Roles, and New Work** and **The Everyone-a-Manager Shift**.

---

## Part A. Research question, objectives, goals and milestones

### Research question

When AI takes on more of an occupation's production work, do employers change what they ask entry-level workers to do: less producing, the work through which juniors have learned, and more checking, directing and coordinating? And do they ask for experience that a newcomer cannot yet have?

### Sub-questions

1. **Shape.** Within an occupation, how does the work asked of entry-level hires differ from the work asked of senior hires? Is the gap larger where AI is used most for that occupation's production tasks?
2. **Change.** Over 2026 to 2028, do entry-level postings change faster in high-use occupations? We follow three things: how many there are, what phase of work they stress, and how much experience they require. Each employer is compared with itself over time.
3. **Hidden practice.** Which routine entry-level tasks give newcomers the practice that later expertise rests on, and which of those tasks is AI now doing?
4. **New skills.** Which human capacities do employers now ask juniors for that they did not ask for before, such as checking a machine's output or judging when to step in?

### Objectives

1. Build an open panel of occupation × seniority × phase of work. It joins three layers:
   - **What the job involves:** O*NET task ratings for 911 occupations.
   - **What employers ask for:** job postings.
   - **Where AI is already used:** two independent usage measures, Microsoft's Working with AI work-activity metrics and the Anthropic Economic Index task file.
2. Measure the "rung gap": how the work asked of entry-level hires differs from the work asked of senior hires, occupation by occupation, and how it moves with AI use.
3. Track entry-level demand monthly in a daily panel of the public job boards of 715 employers.
4. Test with workers' own accounts whether the gaps in postings match what juniors actually do and learn.
5. Release the panel, code and coding guides openly, with a monthly first-rung indicator that policymakers, educators and employers can read.

### Goals

- A book chapter (June 2027) that shows, for named occupations, where juniors still get to practice and where that practice is thinning.
- A journal manuscript (March 2028) with the cross-section results and the first 15 months of the panel.
- A public, monthly-updated first-rung indicator for every occupation with enough postings, on jobs.humanitarians.ai, with the data under CC BY 4.0 and the code under MIT.

### Milestones

| When | Milestone |
|---|---|
| Jan to Apr 2027 (before the award) | [DECIDE] Start saving the text of new postings each week, so the panel has text from January on (today it keeps only title, employer, place and dates; text was saved once, on November 11, 2026). Two people review a stratified sample of title-to-occupation matches and phase tags. Join Microsoft's work-activity metrics to the phase tags. |
| May to Jun 2027 (full-time) | Freeze panel version 1. Cross-section results (sub-question 1) for the 409 occupations with at least 50 matched postings. **Book chapter draft submitted, June 2027.** |
| Jul to Aug 2027 (full-time) | Code the seven capacity facets in entry-level postings at scale: blind model coders, plus a human coder on a 10% sample (sub-question 4). Field the worker-diary pilot if the IRB approves it (sub-question 3). |
| Sep to Dec 2027 | The panel reaches 12 months (October 2027): first estimates of change (sub-question 2). Chapter revised after editorial feedback. Data release version 1. |
| Jan to Mar 2028 | **Manuscript submitted, March 2028.** First-rung indicator goes live and updates monthly. |

---

## Part B. Narrative questions

### 1. Alignment with AIEI themes

The call's First Rung theme asks: "Which apparently routine tasks carry hidden learning, socialization, or signaling value?" and "Who bears the cost of developing future experts?" This project measures that pathway directly.

My earlier work divides every occupation's tasks into six phases: understand, plan, produce, check, sustain and coordinate. It asks two questions of each job: where its work sits, and where AI use already shows up. Juniors have traditionally learned by producing. If AI takes on production while employers keep asking juniors for checking, coordination and judgment, the rung has moved up, and newcomers lose the practice that earned it.

The same frame answers the augmentation theme's question "At what level should augmentation be measured?" Our answer is the phase of work inside each task. That is finer than the occupation and closer to what changes when AI enters a workflow.

It also gives the Everyone-a-Manager theme a measure. The share of entry-level work spent defining goals (plan), evaluating outputs (check) and directing others (coordinate) is a number we can track by occupation over time.

The early evidence is concrete. In a January 2024 snapshot of US LinkedIn postings, 75% of entry-titled accountant postings that state a minimum ask for two or more years of experience (925 postings). Entry-titled postings were 16% of accountant postings that state a minimum, but only about 1% of software-developer postings (55 of 4,700).

### 2. Methodology

**Data, all existing or already being collected:**
- **O*NET 31.0:** task ratings and work-activity links for 911 occupations.
- **A US LinkedIn snapshot of January 2024:** 1,149,342 postings, of which 406,172 were matched to an occupation by title.
- **A daily panel:** every open posting on the public job boards of 715 employers, collected since October 24, 2026 (84,660 open postings on November 22, 2026).
- **Two independent measures of AI use:**
  - the Anthropic Economic Index task-penetration file;
  - Microsoft's Working with AI metrics (Tomlinson et al., NeurIPS 2026, CC BY 4.0). These score each O*NET intermediate work activity separately for AI assisting a user and AI performing the activity.

  Our phase tags sit at the same work-activity level, so the join is direct. Using two vendors' data lets us report where they agree and where they differ.

**Measures:**
- An occupation's phase profile from O*NET task weights.
- A posting profile from phase-diagnostic phrases, split by the level named in the job title (entry, mid, senior, lead).
- The share of entry-titled postings.
- Stated minimum years of experience.
- AI use in each phase, with assistance and performance kept separate.

**Analysis:**
- Sub-question 1 is a cross-section across 409 occupations: the rung gap against AI use in production work, controlling for occupation family.
- Sub-question 2 compares trends within each employer and occupation: high-use against low-use occupations, month by month, in the daily panel.
- Results are descriptive associations, and we will not call them causal effects. The analysis plan will be registered before the panel reaches 12 months.

**AI-enabled coding, checked by people:**
- Model coders work independently, without seeing each other's work, from written coding guides. In pilots, two blind coders agreed with the first coder on 84% and 86% of primary-facet codes (Cohen's kappa 0.78 and 0.82).
- We add a non-Claude model and a trained human coder, and report agreement for every measure. Where coders disagree, those lines go to human review first.
- Replication kits are public, so others can rerun the coding.

**Country comparison:** the same employers' postings in the US and in other countries: the UK, Germany, India, Brazil and others. Today 45% of postings carry a country code; we will fill in the rest from the location text.

**Worker accounts:** [DECIDE] a diary pilot with about 60 consenting Northeastern students on co-op placements, subject to IRB approval. Students log the tasks they do, which ones AI did, and what they learned. It tests whether gaps in postings match the work.

### 3. Anticipated outcomes

1. **A first-rung indicator for every occupation with enough postings**, updated monthly. It shows:
   - the share of entry-titled openings;
   - the experience they ask for;
   - how the work asked of entry-level hires differs from senior hires;
   - AI use in the production work juniors used to do.
2. **A ranked list of the tasks with hidden practice value:** routine tasks that newcomers did, that AI now does, and that later expertise depends on.
3. **A book chapter** written for employers, educators and policymakers.
4. **A journal manuscript.**
5. **Open data, code and coding guides** that other researchers can extend to new occupations, countries and AI-use measures.

### 4. Impact

- **Employers:** evidence for deciding which tasks to keep for juniors when AI could do them. This is the training cost the call asks about: who bears it, and what happens to firms that stop paying it.
- **Educators:** a measure of the gap between what entry-level jobs require and what students can practice. I will use it in my own courses (more than 3,500 students since 2015) and offer it to Northeastern's co-op preparation.
- **Policymakers:** a monthly, occupation-level signal of whether entry-level hiring is shrinking or moving up the ladder, available before the slower official statistics.
- **Workers and students:** jobs.humanitarians.ai already maps Boston employers and research groups. The indicator would show job seekers which first rungs are still open.

### 5. Potential risks and how we handle them

| Risk | Response |
|---|---|
| Wrong title matches or phase tags | Stratified human review before analysis. Independent coding by several models and a person. The disagreements are published. |
| Postings describe recruiting, not work | We report posting emphasis as recruiting emphasis, compare it with O*NET, and check it against workers' diaries. |
| Too short a panel to see change | The cross-section results (sub-question 1) stand on their own. The 2024 LinkedIn snapshot and a 2022 to 2025 data-analyst series give earlier points. |
| The 715 employers lean toward tech | We report coverage by occupation, reweight, and compare with the LinkedIn snapshot. |
| Vendor usage data reflect each vendor's users | Two vendors, agreement reported, and the limits stated: exposure is not replacement. |
| IRB delay | The diary pilot is optional. Sub-questions 1, 2 and 4 do not depend on it. |
| Rights in posting text | No posting text is published, only derived counts and codes. |

---

## Target journals (up to three)

1. **PNAS Nexus** (open access): broad reach to economists and policymakers.
2. **EPJ Data Science** (open access): computational social science and methods from job-posting data.
3. **Journal for Labour Market Research** (open access): labor economics.

[CHECK: whether article fees can come from the gift.]
