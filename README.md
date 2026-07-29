# Y4hrware Offsets Fallback

Public fallback used by Y4hrware when `offsets.imtheo.lol` is unavailable.

The application accepts `FFlags.json` only when:

- `Roblox Version` matches the current Roblox live version;
- `Total Offsets` is greater than zero;
- the `FFlagOffsets` object exists.

The scheduled GitHub Action refreshes the file from imtheo every 15 minutes.
It can also be started manually from the Actions tab.

Raw fallback URL:

```text
https://raw.githubusercontent.com/yasuogoat3/y4hrware-offsets/main/FFlags.json
```

Never add a GitHub token to the Y4hrware client or launcher.
