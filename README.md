# new-opportunity-example
Demonstration project

### Why submodules?

Sub-projects use different build tools (maven and gradle).

Note that to be on the safe side, you should run git submodule update with the `--init` flag in case commits you just pulled added new submodules.
If you want to automate this process, you can add the `--recurse-submodules` flag to the git pull command (since Git 2.14). This will make Git run git submodule update right after the pull, putting the submodules in the correct state.

