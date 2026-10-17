# PATCH repos

How code from a PATCH lab gets into this org, and how the org profile stays current.
PATCH itself is defined in the [Community Handbook glossary](https://github.com/philaconvalley/community-handbook/blob/main/foundation/glossary.md).

**Owner:** Waskar Paulino. He does both steps below during the debrief of each PATCH.

## 1. Name and tag the repo

A PATCH that produces code gets one public repo.

- **Name:** `patch-<number>-<name>`, for example `patch-003-projection-mapping`. Use three digits and
  lowercase words. The planning folder for the same event uses the same pattern.
- **Topic:** add `patch-series`. The profile links to that topic, so a tagged repo appears there
  with no other step.
- **Template:** turn on **Template repository** in Settings if attendees start from the code.
- **Demo:** if the code runs in a browser, turn on GitHub Pages and put the URL in the repo's
  website field.

A PATCH with no code, such as PATCH 002, gets no repo.

### Repos from before this rule

`djVisualizer` (PATCH 001) and `projectionMapper` (PATCH 003) keep their names. Attendees already
have those links, and a rename breaks the GitHub Pages URL. GitHub redirects the repo page, but
not the Pages site.

## 2. Add the row to the profile table

Edit [`profile/README.md`](profile/README.md). Add one row to the PATCH table:

| Column | What to write |
|---|---|
| Lab | The name from the Luma listing, for example `PATCH 003: Projection Mapping Lab` |
| What you build | What an attendee leaves with, in a few words |
| Code | A link to the repo, and a `try it` link if it has a live demo. With no repo, write that. |

Open a pull request. The row goes live when it merges.
