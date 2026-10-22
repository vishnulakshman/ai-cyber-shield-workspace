# Password Policy Specification

## Business Rules
1. **Minimum Length:** A password must be at least 8 characters long.
2. **Character Complexity:** A password must contain at least 1 number (digit 0–9).

## Operational Scope & Boundaries
- **Length Boundary:** Validated strictly at < 8 characters (Rejection) vs. >= 8 characters (Acceptance).
- **Complexity Boundary:** Validated strictly as missing a number (Rejection) vs. containing at least 1 number in any position (Acceptance).
- **Unstated Conditions:** Maximum length, allowed character sets, whitespace handling, and error message text are not defined in this policy. Do not introduce unstated requirements without product authorization.