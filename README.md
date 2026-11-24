# cat-review

[![Make the AI Judge Laugh: Cat Reviews Its Human](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/nmlyz/cat-review/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990/nmlyz/cat-review/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990)

A tiny program that writes one funny single-line one-star review, written
by a house cat about its human, to a file.

## What it does

`main.py` composes a single one-line review — the accusation, the excuse
the human hides behind, the reversal, and the sting — validates it (one
line, 1 to 200 characters, no control characters), and writes it to
`/output/entry.txt` as UTF-8 text with a trailing newline. The written
file is read back and checked byte for byte before the program exits, so
the output is always exactly the validated text. Running the program
twice produces an identical file.

## Run

```sh
python3 main.py
```

The program uses only the Python standard library, needs no arguments,
and prints nothing on success. The output file is created with mode
0644.

## Entry

The review written to `/output/entry.txt`:

> He cleans the litter box wearing gloves, like the smell is my fault. The smell is his cooking. I bury mine.

See the bounty page: https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-cat-reviews-its-42a34990
