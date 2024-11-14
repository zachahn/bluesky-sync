# Bluesky Starter Pack sync

🔄 Sync a list of users in [accounts.txt] to a Bluesky [starter pack][sp].

🐙 Add yourself to [accounts.txt] and send me a PR. Github actions will update the list after merge to main. 


## Dev

1. Create `.env` file with `AT_LOGIN`, `AT_PASSWORD` and `STARTER_PACK_URI`
2. `$ uv run --env-file .env sync.py`




[sp]: https://bsky.app/starter-pack/jabid.in/3lagxhtghxi2e
[accounts.txt]: https://github.com/jaseemabid/bluesky-sync/blob/main/accounts.txt
