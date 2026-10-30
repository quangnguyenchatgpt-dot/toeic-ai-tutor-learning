# TOEIC AI Tutor Learning

Personalized English learning system: zero foundation to TOEIC Listening & Reading 900+, with workplace English for IT/RPA.

- Schedule: 3 sessions per week, 60 minutes per session, session-based (no fixed weekdays).
- Pedagogy: 20% theory, 80% practice, review, and assessment.
- Curriculum: 6 phases and a baseline of 696 sessions (adaptive, not a mandatory duration).
- Python: >=3.9.
- Agents: OpenAI Codex and Google Antigravity.
- Progress is never marked completed or pushed without learner approval.

## Repository status

This repository is being bootstrapped. The full previously generated project bundle is available in the original ChatGPT conversation. Until imported, **do not assume** that the 696 session plans, Excel workbook, and seven tests are present in GitHub.

## Local import of the previously generated archive

Download `toeic-ai-tutor-learning.zip` from the ChatGPT conversation and extract its **contents** into the root of this repository. Then run:

```bash
python -m pip install -r requirements.txt
python scripts/validate_project.py
python -m unittest discover -s tests -v
python scripts/next_session.py
```

Review the changes before committing. Preserve learner progress and avoid overwriting an existing `learning/progress.json`.

## Agent entry point

Read [AGENTS.md](AGENTS.md) before teaching or modifying the project.
