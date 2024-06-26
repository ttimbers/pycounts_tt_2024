# pycounts_tt_2024

[![Documentation Status](https://readthedocs.org/projects/pycounts-tt-2024/badge/?version=latest)](https://pycounts-tt-2024.readthedocs.io/en/latest/?badge=latest)

[![codecov](https://codecov.io/gh/ttimbers/pycounts_tt_2024/graph/badge.svg?token=0KMZ9OEBGI)](https://codecov.io/gh/ttimbers/pycounts_tt_2024)

Author: Tiffany-Anne Timbers

Calculate word counts in a text file!!!

## Installation

```bash
$ pip install pycounts_tt_2024
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts.pycounts import count_words
from pycounts.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```


## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_tt_2024` was created by Tiffany Timbers. It is licensed under the terms of the MIT license.

## Credits

`pycounts_tt_2024` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
