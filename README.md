# Medical Bill Fighter (by Zelda Rose)

`index.html` is the whole tool. It's one file, with no dependencies and no backend, no cookies, analytics, or network requests. It works offline. To use it, open the file in any browser.

What it does:
1. **Action-plan wizard**: answer 8 quick questions and get a plan for your situation (collections, surprise bills, denials, charity care, self-pay).
2. **Bill checker**: paste itemized lines. It flags possible duplicates, vague descriptions, missing codes, high quantities, dates outside your stay, and room charges on the discharge day.
3. **Letter generator**: 7 templates (itemized bill, financial assistance/charity care, error dispute, self-pay discount/payment plan, FDCPA debt validation, No Surprises Act dispute, insurance internal appeal). You can copy, print or save as PDF, or download as .txt. Flags from the checker can be dropped straight into the dispute letter.
4. Phone scripts, a summary of your rights with official source links, free-help directory, and an optional crypto tip section.

Verified (Oct 17, 2026): html-validate (recommended ruleset) passes; a headless Chrome functional test ran with zero JS errors and no external requests; all 7 letters render; tip addresses match the originals exactly.
