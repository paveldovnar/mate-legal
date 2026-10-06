# What was stripped from the source texts

Sources (unchanged): `docs/legal/terms-of-use-draft.md`, `docs/legal/privacy-policy-draft.md`.
Delete this file before publishing if you do not want it in the site.

## terms/index.html

1. Opening blockquote, entire: "DRAFT — NOT REVIEWED BY A LAWYER ... written by a project session on 1 Oct 2026 ... owner decided ... no lawyer review ... sections (§7, §10, §11, §15) ... One blank remains: the state the LLC is registered in (§15)."
2. Line "Version of this document: draft 0.1 · 1 October 2026" replaced by "Effective date: 6 October 2026".
3. `_[TO FILL: URL]_` in §13 replaced by `https://mateapp.org/terms/` (linked).
4. Blockquote after Appendix A item 10, entire: "Check before submission. Apple publishes these as ... Re-read that list against this appendix at submission time — Apple revises it."
5. The trailing `---` rule and everything after it, to the end of the file: section "Open items for the publisher" (4 blanks list) and table "Decisions settled by the owner, 1 October 2026".

## privacy/index.html

1. Opening blockquote, entire: "DRAFT — NOT REVIEWED BY A LAWYER ... every factual statement checked against the source code of this repository ... the owner decided ... no lawyer review ... Two facts about the company remain to be filled in."
2. Line "Version of this draft: 0.1 · 1 October 2026" replaced by "Effective date: 6 October 2026".
3. Marker "[LAWYER]" removed from the heading of §7 (now "7. Your rights").
4. `_[TO FILL: URL]_` in §8 replaced by `https://mateapp.org/privacy/` (linked).
5. §9 Contact: paragraph "The Telegram link currently in the app is a placeholder; a real support account will be created. App Store review generally expects an e-mail address or a web form in addition to a messenger."
6. The `---` rule and the whole "Appendix — how the facts above were verified" (table of claims checked against repository files, SDK names searched, Package.swift, KeychainSeedVault.swift, project.yml, etc.).

## Deliberately NOT changed (owner may want to review)

Legal wording was left as is, so these drafting-commentary passages remain in terms/index.html:
- §7 paragraph "What this clause does and does not do — stated plainly." (mentions Apple's minimum-terms requirement and that no checks are run)
- §10 paragraph "Why this is drafted the way it is." (mentions courts striking down clauses)
- §15 paragraphs "One honest limit on this section." and "What is deliberately not here." (explains why no arbitration or class-action waiver)
- §10.3 contains the word "free" ("the app is free and we charge no service fee"); §1 contains "yield" and "investment return" in a negative statement (the app offers none). Marketing-word ban applied only to index and support pages.
- Terms §1.1 blockquote (USD-equivalent disclosure) is kept as a blockquote on purpose.
- Terms and Privacy mention Wyoming as governing law (already filled in the source).

## Дополнительно (CTO, 06.10)
Из terms убраны авторские пояснения: §7 «What this clause does and does not do — stated plainly», §10 «Why this is drafted the way it is»; §15 «What is deliberately not here» сокращён до одной фразы «There is no mandatory arbitration clause and no class-action waiver.»; «One honest limit on this section.» переименован в «Consumer rights.» (текст защиты потребителя оставлен).
