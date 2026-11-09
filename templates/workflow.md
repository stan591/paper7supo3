# Workflow

## 5 Nov 2026 – Choosing the question
- Action and reason: Brainstormed project ideas linked to Lectures 1–8. Chose remote work and the London wage premium because theory gives competing predictions (dispersion vs NEG agglomeration) and the data is free and annual.
- Change made: Wrote the question, two mechanisms and hypothesis (modest dispersion) before looking at the data.
- Check and result: Checked the hypothesis was internally consistent; revised it so the reasoning (hybrid work limits moves) matched the prediction (only a modest fall).
- Next step: Download earnings data.

## 6 Nov 2026 – Data and first chart
- Action and reason: Downloaded ASHE median full-time weekly pay from the Nomis API (residence and workplace analyses) so the analysis is reproducible.
- Change made: Built Figure 1 (London premium, workplace vs residence).
- Check and result: Data shape correct (14 areas × all years); 2020 spike identified as a furlough/lockdown distortion, so 2020–21 excluded.
- Next step: Compare pre- and post-COVID periods.

## 8 Nov 2026 – Extending and testing
- Action and reason: Tested whether the high pre-2012 premium reflected the 2008 financial crisis by extending the data back to 2002.
- Change made: Data now covers 2002–2025; added Table 1 comparing 2002–07, 2017–19 and 2022–25.
- Check and result: Premium was already ~1.28 before 2008, so the crisis idea was not supported. Post-COVID decline (~0.16 pts/year) no faster than the pre-COVID trend (~0.2 pts/year).
- Next step: Test whether a stable London average hides workers moving out.

## 8 Nov 2026 – Commuter belt test
- Action and reason: A stable London average could hide movers being replaced, so I checked where movers would go (South East and East), with the North West as a control.
- Change made: Added Figure 2 and Table 2 (residence ÷ workplace pay ratio by region).
- Check and result: No meaningful change in any region; the commuter belt matched the control, so the cancelling-out explanation looks unlikely.
- Next step: Validate the data and write up.

## 8 Nov 2026 – Validation
- Action and reason: Checked the downloaded data against official published figures.
- Change made: Ran a validation check in Colab (not included in the uploaded notebook).
- Check and result: UK 2024 (£728.3) and 2025 (£766.6), and Wales 2025 workplace (£704.3) and residence (£719.3), match the ONS and Welsh Government bulletins exactly.
- Next step: Upload to GitHub.

## Tools / AI assistance
- Tool and request: Python (pandas, matplotlib) in Google Colab; Nomis API for data. Claude (AI assistant) to brainstorm questions, explain the theory, write and debug Python code, and review my drafts.
- Contribution: Claude suggested data sources and code, explained concepts I found difficult, and drafted the overview and some wording. The question choice, interpretation and conclusions are my own.
- Checks or changes: Validated the data against ONS figures; checked quotes against lecture slides and sources; rewrote AI-suggested text in my own words where possible.
