# MSCS-Graduate-Final-Thesis---Uri-Promentilla
Daily Progress of my Master's Thesis

# Thesis Daily Notes

Purpose
- Keep a daily log of progress for my master's thesis.
- Each day, add a file `daily-notes/YYYY-MM-DD.md` with a short, consistent summary.
- Commit locally and sign commits with your GPG key before pushing to GitHub to produce verifiable authorship and timestamps.

How to use
1. Clone or create this repository.
2. Make sure you have Git and GPG installed.
3. Generate a GPG key (or use an existing one) and add the public key to your GitHub account.
4. Use `scripts/create_note.sh` to create today's note, edit it, then `git add`, `git commit -S -m "Daily notes: YYYY-MM-DD"`, and `git push`.
5. Optionally, use OpenTimestamps to anchor the note's hash for independent public proof.

Recommended note filename
- `daily-notes/2026-01-07.md` (YYYY-MM-DD)

Note content suggestions
- Title / Date
- Objective for the day
- What I did (concise bullet points)
- Artifacts (links to code, figures, screenshots)
- Time spent (hours)
- Unresolved issues / next steps

Security & verification tips
- Sign commits with GPG (`git commit -S`) and publish your public key on GitHub. GitHub displays "Verified" on signed commits.
- To create an independent public timestamp for a file, use OpenTimestamps (ots) to stamp the file hash; the resulting timestamp can be verified later.
