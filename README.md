[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vlipiainen/openphil-analysis-graphics/HEAD) [![Produce_graphics](https://github.com/vlipiainen/openphil-analysis-graphics/actions/workflows/produce_graphics.yml/badge.svg)](https://github.com/vlipiainen/openphil-analysis-graphics/actions/workflows/produce_graphics.yml)

# Plotting Open Philanthropy data

Quickly made jupyter notebooks for making simple graphics about Open Philanthropy funding. Data automatically downloaded from Open Philanthropy's [Grants Database](https://www.openphilanthropy.org/giving/grants).

## Available graphs
- All funding Open Philanthropy has given since the start of their database, separated by Focus Area.
- Distribution of funding accross the 6 largest Focus Areas for every year.
- Funding per Focus Area for a given year (by default 2021, you'll have to make your own or ask me if you want something else).
- Funding per Focus Area from the beginning of 2021 to the current day.
- Feel free to leave an issue request if you'd like some other graph

## How to get and edit graphs
1. A github action builds and commits a default set into the directory `pngs`. In some cases these might be out of date, depending on when the last commit was.

2. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/vlipiainen/openphil-analysis-graphics/HEAD) If you want to make changes, the simplest way is to launch a binderhub based on this repository:  There you can edit the notebooks as you wish and download the results. Bear in mind that any changes will be lost after your session closes.

3. All the jupyter notebooks are meant to be self-contained, so you can copy any of them to your computer and edit as you wish. The file `requirements.txt` describes all necessary dependencies (they can be installed via `pip install -r requirements.txt`).