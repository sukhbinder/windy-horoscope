# winzy-horoscope

[![PyPI](https://img.shields.io/pypi/v/winzy-horoscope.svg)](https://pypi.org/project/winzy-horoscope/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/winzy-horoscope?include_prereleases&label=changelog)](https://github.com/sukhbinder/winzy-horoscope/releases)
[![Tests](https://github.com/sukhbinder/winzy-horoscope/workflows/Test/badge.svg)](https://github.com/sukhbinder/winzy-horoscope/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/winzy-horoscope/blob/main/LICENSE)

Get daily Horoscope using https://horoscope-app-api.vercel.app by Ashutosh Krishna

## Installation

First [install winzy](https://github.com/sukhbinder/winzy) by typing

```bash
pip install winzy
```

Then install this plugin in the same environment as your Winzy application.
```bash
winzy install winzy-horoscope
```
## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd winzy-horoscope
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
