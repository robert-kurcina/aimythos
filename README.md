# aimythos
## An LLM engine for running Mythos games.

### Option A - Manual Upload
For this option, you manually interact with the prompt interface for all fies.
1. You'll need to download all of the files from this repo from /src
2. Open Qwen3-Max and upload all 6 files. Qwen allows just 5 files at a time.
3. Paste this into the Qwen prompt:

`Read and parse the uploaded files. Begin the game as described.`

### Option B - Single GitHub Call
For this option, you just copy and paste this command into the LLM prompt:

```text
Access these files at:

https://raw.githubusercontent.com/robert-kurcina/aimythos/refs/heads/main/src/dagon-qwen-mythos-outlay.json
https://raw.githubusercontent.com/robert-kurcina/aimythos/refs/heads/main/src/dagon-qwen-character-system.json
https://raw.githubusercontent.com/robert-kurcina/aimythos/refs/heads/main/src/dagon-qwen-scenario-outlay-ram.json
https://raw.githubusercontent.com/robert-kurcina/aimythos/refs/heads/main/src/dagon-qwen-scenario-outlay-castine.json
https://raw.githubusercontent.com/robert-kurcina/aimythos/refs/heads/main/src/dagon-qwen-scenario-outlay-boothbay.json

Read and parse the files. Play the game as described.
```

## Screenshots
![Overview](/img/overview.png)

![Scenarios](/img/scenarios.png)

