# World News in One Image — 24 November 2026

![make.fun](https://make.fun/badge/news-image-20261124.svg)
![rank](https://make.fun/badge/news-image-20261124/muammarkhadafi/makefun-news-image/rank.svg)
![reward](https://make.fun/badge/news-image-20261124/muammarkhadafi/makefun-news-image/reward.svg)

One image summing up the world news of Tuesday, 24 November 2026, for the
[make.fun bounty](https://make.fun/bounty/news-image-20261124).

The image is a newspaper-style front page drawn from the day's reporting:
the ICJ genocide ruling on Myanmar winning the backing of fourteen nations,
NATO's warning over a possible Russian nuclear satellite, Nvidia reinstating
Jensen Huang as markets surged, the US drone-assisted capture of
"El Chapo Isidro" in Mexico, the COP31 climate summit ending with no deal,
and fighting trapping Ebola responders in DR Congo.

## Entry

`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png`. The run is deterministic: both runs write the same
bytes.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`entry.png` is 1024x1024, under 1 MiB.
