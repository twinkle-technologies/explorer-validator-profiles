# Explorer Validator Profile-

Submitting a profile here is **optional** (if we can use the on-chain data - we'll use the on-chain way). However, for some networks (e.g., [Story](https://story.explorers.guru)), this is the only way to display additional validator information.

## How to Add Your Validator Info

1. **Create a `.json` file** named `$YOUR_ONCHAIN_IDENTITY.json` in the [profiles](https://github.com/NodesGuru/explorer-validator-profiles/tree/main/profiles) folder.

2. **Fill it out** following the [example](https://github.com/NodesGuru/explorer-validator-profiles/blob/main/profiles/28B672FCE6BBD562.json):

   > ⚠️ **The `addresses` field is required for chains where setting the `identity` is not possible.**

   Example:
   ```json
   {
     "icon": "https://raw.githubusercontent.com/NodesGuru/explorer-validator-profiles/main/images/28B672FCE6BBD562.png",
     "description": "Guru of non-custodial staking. Professional node runner, low fees, best uptime, and 24/7 customer support.",
     "socials": {
       "email": "security@nodes.guru",
       "website": "https://nodes.guru/staking",
       "github": "https://github.com/nodesguru",
       "twitter": "https://x.com/NodesGuru",
       "telegram": "https://t.me/NodesGuruStake",
       "discord": ""
     },
     "addresses": [
       "storyvaloper18fru7pm6mdtgqlfttwxl3d3mwv2nevhtsfl8wh"
     ]
   }
   ```

3. **Upload your validator logo** to the [images](https://github.com/NodesGuru/explorer-validator-profiles/tree/main/images) folder.

   The logo file must be named exactly as `$YOUR_ONCHAIN_IDENTITY.png`.

4. **Create a pull request** including:

   - Your `.json` profile file.
   - Your validator logo image.
