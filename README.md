# IELTS homework portal

One link for students. Four tasks, each handed in separately:

- Listening and reading, with a dictation and paraphrase-pair gate
- Writing, 20 + 40 minutes on a server-free enforced clock, paste blocked
- Speaking, the full 15-minute test, recorded per part with a transcript
- Vocabulary, ten words at ten seconds each, then three sentences

Everything a week needs lives in one block of `WEEKS` at the top of
`index.html`: the L&R brief, both writing prompts, the speaking set and
the ten words with Vietnamese glosses.

`CONFIG.endpoint` is the Apps Script web app that receives submissions.
While it is empty the portal falls back to download buttons, so no work
is ever lost.

Students need Chrome on a laptop with headphones.
