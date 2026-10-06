# copilot-common

## What it does

Shared rules and readers used by every department copilot: privacy rules, document/spreadsheet/screenshot readers, writing helper.

Part of the **department-copilots** suite: local-only copilots where the employee provides the input, Claude analyses it on the machine, and the employee decides what to do. No CRM, NMS, email or system integrations.

## Install

```bash
claude plugin marketplace add sara-hamza/department-copilots
```

```bash
claude plugin install copilot-common@department-copilots
```

Shared skills used by every department copilot. Skills only, no commands.

| Skill | Purpose |
|---|---|
| `privacy-rules` | The local-only operating contract every copilot applies first |
| `document-reader` | How to read PDFs, Word docs and text the employee drops in |
| `spreadsheet-reader` | How to profile CSV/XLSX exports (`scripts/profile_sheet.py`) |
| `screenshot-reader` | How to extract structured facts from screenshots |
| `writing-helper` | House style for drafts: tone, structure, Australian English |
