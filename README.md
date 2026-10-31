# shopkit (demo repo)

A small Python library with bugs planted on purpose, used to demo
[github-issue-coding-agent](https://github.com/thousif-ai-portfolio/github-issue-coding-agent).

Each bug is reported as an issue here. The agent reads the issue, writes a test that
reproduces it, fixes the code, runs the tests in a Docker sandbox and, after a person
approves, opens a **draft pull request** in this repository.

```bash
python -m pytest
```
