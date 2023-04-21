# python-boilerplate

> Boilerplates are like toothbrushes. Everyone has one and no one wants to use anyone else's.
> 
> This one is mine.

## Prerequisites

- [Python](https://www.python.org)
- [pyenv](https://github.com/pyenv/pyenv)
- [Poetry](https://python-poetry.org)

## Dependencies

- [Black](https://pypi.org/project/black/)
- [Flake8](https://flake8.pycqa.org/en/latest/)
- [mypy](https://www.mypy-lang.org)
- [pytest](https://pytest.org/)

## Usage

### Run the script

1. Open a terminal window at the root of this project

2. Run the following commands:

```shell
## Install dependencies
poetry install

## Run main script
poetry run ./src/myproject/main.py
```

### Additional commands

```
## Lint with flake8
poetry run flake8 .

## Lint with black
poetry run black .

## Check static typing with mypy
poetry run mypy .

## Test with pytest
poetry run pytest

## Update dependencies
poetry update
```

## License

The MIT License (MIT)

Copyright (c) 2022 Dane Petersen
