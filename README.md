# napari-matplotlib

[![License](https://img.shields.io/pypi/l/napari-matplotlib.svg?color=green)](https://github.com/matplotlib/napari-matplotlib/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/napari-matplotlib.svg?color=green)](https://pypi.org/project/napari-matplotlib)
[![Python Version](https://img.shields.io/pypi/pyversions/napari-matplotlib.svg?color=green)](https://python.org)
[![tests](https://github.com/matplotlib/napari-matplotlib/workflows/tests/badge.svg)](https://github.com/matplotlib/napari-matplotlib/actions)
[![codecov](https://codecov.io/gh/matplotlib/napari-matplotlib/branch/main/graph/badge.svg)](https://codecov.io/gh/matplotlib/napari-matplotlib)
[![readthedocs](https://readthedocs.org/projects/napari-matplotlib/badge/?version=latest)](https://napari-matplotlib.readthedocs.io/en/latest/)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/matplotlib/pytest-mpl/master.svg)](https://results.pre-commit.ci/latest/github/matplotlib/pytest-mpl/master)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/napari-matplotlib)](https://napari-hub.org/plugins/napari-matplotlib)

A plugin to create Matplotlib plots from napari layers

----------------------------------

## Introduction
`napari-matplotlib` is a bridge between `napari` and `matplotlib`, making it easy to create publication quality `Matplotlib` plots based on the data loaded in `napari` layers.

## Available widgets

### `Slice`
Plots 1D slices of data along a specified axis.
![](https://raw.githubusercontent.com/matplotlib/napari-matplotlib/main/examples/slice.png)

### `Histogram`
Plots histograms of individual image layers, or RGB histograms of an RGB image
![](https://raw.githubusercontent.com/matplotlib/napari-matplotlib/main/examples/hist.png)

### `Scatter`
Scatters the values of two similarly sized images layers against each other.
![](https://raw.githubusercontent.com/matplotlib/napari-matplotlib/main/examples/scatter.png)

## Installation

You can install `napari-matplotlib` via [pip]:

    pip install napari-matplotlib



To install latest development version :

    pip install git+https://github.com/matplotlib/napari-matplotlib.git


## Contributing

Contributions are very welcome! Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [BSD-3] license,
`napari-matplotlib` is free and open source software.

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[@napari]: https://github.com/napari
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause

[file an issue]: https://github.com/dstansby/napari-matplotlib/issues

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
