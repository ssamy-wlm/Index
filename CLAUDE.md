# WebLight Media Library — Git Workflow

For any change to this repo, handle the entire git process end to end without asking the user to do any of it.

- Make the code change.
- Show the finished change (the record, the diff, or the before/after) for a quick content confirmation. Flag any risky side effects (exclusion arrays, override arrays, shared templates) as has been standard in this project.
- On approval, do everything else automatically: stage, commit with a clear message, push, open the pull request, merge it to `main`, and confirm it's live. Then give the changed-lines report.
- The user should never have to open, push, approve, or merge a PR themselves. If a merge conflict or CI failure blocks the automatic merge, resolve it if it's safe, or stop and tell the user exactly what's wrong — don't leave a PR half-open without saying so.
- Keep the existing review habits: verify changes against the live data before reporting done, and never delete or reassign a record without flagging it first.
