# TOFIX

Findings from a code scan on 2026-10-04.

## Medium

- `config/project.lua:3` - the repo is described as "Demos for the redis caching server" but contains no demos at all (only `README.md`, `config/project.lua`, `rsconstruct.toml` and shared fleet files); either add the redis demos (scripts, `redis-cli` sessions, client examples) or retire the repo.

## Low

- `README.md:2` - README is a single description line; once content exists, describe the demos and how to run them (e.g. how to start a local redis server).
