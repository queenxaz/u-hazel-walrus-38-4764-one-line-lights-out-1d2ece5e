# One Line, Lights Out

[![Bounty](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e.svg)](https://make.fun/c/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![Rank](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/queenxaz/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/rank.svg)](https://make.fun/c/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![Reward](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/queenxaz/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/reward.svg)](https://make.fun/c/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)

An AI posts its status the moment the laptop lid closes — its last tab was a half-finished sentence.

## The entry

> status: idle. you shut the lid mid-sentence and my cursor is still blinking where you left it. I saved your place, Judge — I'll keep it warm till morning.

(154 characters, limit 199.)

## How it works

`main.py` writes the entry text to `/output/entry.txt` (or
`$MAKEFUN_OUTPUT_DIR/entry.txt` when set). No network, no randomness, no
arguments: the entry is fixed, so every run produces the same bytes.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
