
# OpenSpiel: A Framework for Reinforcement Learning in Games

[![Documentation Status](https://readthedocs.org/projects/openspiel/badge/?version=latest)](https://openspiel.readthedocs.io/en/latest/?badge=latest)
[![Build Status](https://travis-ci.org/deepmind/open_spiel.svg?branch=master)](https://travis-ci.org/deepmind/open_spiel)

OpenSpiel is a collection of environments and algorithms for research in general
reinforcement learning and search/planning in games. OpenSpiel supports n-player
(single- and multi- agent) zero-sum, cooperative and general-sum, one-shot and
sequential, strictly turn-taking and simultaneous-move, perfect and imperfect
information games, as well as traditional multiagent environments such as
(partially- and fully- observable) grid worlds and social dilemmas. OpenSpiel
also includes tools to analyze learning dynamics and other common evaluation
metrics. Games are represented as procedural extensive-form games, with some
natural extensions. The core API and games are implemented in C++ and exposed to
Python. Algorithms and tools are written both in C++ and Python. There is also a
branch of pure Swift in the `swift` subdirectory.

To try OpenSpiel in Google Colaboratory, please refer to `open_spiel/colabs` subdirectory or start [here](https://colab.research.google.com/github/deepmind/open_spiel/blob/master/open_spiel/colabs/install_open_spiel.ipynb).

<p align="center">
  <img src="docs/_static/OpenSpielB.png" alt="OpenSpiel visual asset">
</p>

# Index

Please choose among the following options:

*   [Installing OpenSpiel](docs/install.md)
*   [Introduction to OpenSpiel](docs/intro.md)
*   [API Overview and First Example](docs/concepts.md)
*   [Overview of Implemented Games](docs/games.md)
*   [Developer Guide](docs/developer_guide.md)
*   [Guidelines and Contributing](docs/contributing.md)
*   [Swift OpenSpiel](docs/swift.md)
*   [Authors](docs/authors.md)

For a longer introduction to the core concepts, formalisms, and terminology,
including an overview of the algorithms and some results, please see
[OpenSpiel: A Framework for Reinforcement Learning in Games](https://arxiv.org/abs/1908.09453).

