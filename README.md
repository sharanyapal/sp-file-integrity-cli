# Integrity Manifest CLI

> **Verify file integrity through transparent, repeatable checks.**

**Security & reliability** &nbsp;·&nbsp; **Python** &nbsp;·&nbsp; **Local-first reference**

[The idea](#the-idea) / [Try it](#try-it-locally) / [Project anatomy](#project-anatomy) / [Assumptions](#assumptions--boundaries)

---

## The idea

SHA-256 manifest creation and safe verification with path traversal protection.

The project is intentionally approachable: source, sample data and verification files are visible in one repository so the behavior is easier to trace.

## Try it locally

```bash
python main.py
```

Review `requirements.txt` if additional packages are required.

## Project anatomy

| File or folder | Role |
|---|---|
| [`README.md`](./README.md) | Project documentation |
| [`main.py`](./main.py) | Python entry point and core program |
| [`requirements.txt`](./requirements.txt) | Environment dependencies |
| [`test_main.py`](./test_main.py) | Tests for implemented behavior |

## Assumptions & boundaries

- Evaluate outputs with controlled, non-sensitive test inputs.
- Confirm edge cases and error handling before applying the code elsewhere.
- Educational examples and synthetic datasets should not be confused with real banking, security or operational infrastructure.

## Original notes

<details>
<summary>Expand original setup instructions and background</summary>

# Integrity Manifest CLI

SHA-256 manifest creation and safe verification with path traversal protection.

## Run

```bash
python main.py
```


No third-party dependencies are required.

## Notes

Demonstration code uses local, synthetic, or publicly available sample data. No proprietary banking/client data.


---

**Part of Sharanya Pal's coding portfolio:** https://sharanya-pal-cinematic-portfolio.vercel.app/#lab-vault  \n**GitHub repository:** https://github.com/sharanyapal/sp-file-integrity-cli

</details>

---

<sub>[Portfolio directory](https://github.com/sharanyapal?tab=repositories) · Source-first documentation, with no unverified performance claims.</sub>
