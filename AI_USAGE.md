# AI tool usage

## Tools and assistance

This project was implemented with an AI coding assistant in VS Code using Copilot SDK. The assistant helped inspect the starter project, implement the FastAPI CSV endpoint and deterministic categorization rules, build the Next.js upload/review interface, write documentation and tests, and run the available checks.

The application does not use GPT, Claude, Gemini, or another large model to decide transaction categories. Categorization is performed by explicit local phrase rules documented in [DESIGN.md](./DESIGN.md).

## Review and corrections

AI-generated code and recommendations were checked rather than assumed correct. Automated tests cover unknown merchants, signed and debit/credit amount formats, transfers, refunds, and upload validation. A phrase match is not a tax determination; users must review uncertain transactions and tax context.

## Token usage and logs

The VS Code/Copilot interface available for this implementation did not expose a verifiable per-task token count or downloadable token log or screenshot. No token count is estimated or fabricated. Attach an official usage screenshot or export from the account/tool dashboard if one is available; until then, token usage is **not available**.
