# Managing Your Saves

- Use any Git tree viewer of your choice to fully visualize the Git structure
  - VSCode Extension [Git Graph v3](https://marketplace.visualstudio.com/items?itemName=Gxl.git-graph-3) (recommended)
- Please consider forking this repository to your account
  1. Clone this repository. (You'll have full freedom this way)
  - Cloning your fork might miss some tags in your local Git repo, but still works.
  2. Add your fork as another remote in your local clone after forking and make it default.
  3. Commit your save exports and push to your fork.

# Note to Speedrunning
- This repository is only meant for saving history of a run, and cannot be used to prove run integrity, due to inconsistencies in exporting and importing saves.
- Even though a run can be saved here, but it is recommended to record your run with OBS.

# Contributing Saves

- Branch names are in the format of `<user>-<UniqueRunID>`
- All commits are preferred to be signed. (If not signed, will be re-committed with the merger's PGP signature)
- Needs to follow a similar structure to the branches and commits, any existing branch can be used as an example.
  1. Saves needs to be inside one sub-folder representing a chapter. `## - Chapter`
  2. Must be in chronological order with .sav extension `### - Description.sav`, the `###` is independent of their folders and unique in a branch.
- Only one branch per run, no hard-resets allowed in-between.
  - The Branch's first commit must mention the game versions.
- Please do mention used mods / exploits in README if found.

## For spoiler-free branches

- Branch name `<user>-<UniqueRunID>-<spoilerfree>` is allowed only if the below conditions are satisfied.
- The README.md needs to contain a next spoiler level tag-url on every commit, only the last commit is allowed to have an invalid future tag-url
- Adding tag-urls before actually creating tags is something needs getting used to, this is a requirement to properly add spoilers in GitHub.
  - Tags represent a checkpoint in time and are used to prevent spoiling content to be displayed.
  - Tag ID needs to be a 8 bytes. (16 character long hex string will do).
- these will be listed in the main page with higher priority but tags are needed.
- There is already one example spoiler-free run for you to explore.
