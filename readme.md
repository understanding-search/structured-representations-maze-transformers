# Structured World Representations in Maze-Solving Transformers

This repository contains notebooks for replicating the results of the paper "Structured World Representations in Maze-Solving Transformers". The paper can currently be found on ArXiv as [2312.02566](https://arxiv.org/abs/2312.02566). Our accompanying blog post can be found at [unsearch.org/research/01_maze_transformer_world_representations](https://unsearch.org/research/01_maze_transformer_world_representations/) (also see the [twitter thread](https://twitter.com/afspies/status/1733070221865341226)).

This repository contains only finalized notebooks for the ArXiv and UniReps 2023 papers, which depend on our base libraries to work:

 - [maze-dataset](https://github.com/understanding-search/maze-dataset) for dataset generation, manipulation, and visualization
 - [maze-transformer](https://github.com/understanding-search/maze-transformer) for model training, evaluation, and analysis

This repository will not be updated with future results, but the base libraries may change. For latest updates, see [unsearch.org](https://unsearch.org/).


# Installation

To install this project with dependencies, we recommend using [poetry](https://python-poetry.org/), but pip is also supported. Simply clone and install:

```bash
git clone https://github.com/understanding-search/structured-representations-maze-transformers
cd structured-representations-maze-transformers
# install via poetry
poetry install
# or with pip
pip install -e .
```

# Usage

Notebooks and required model files are located in the `notebooks` directory. If using poetry, select the initialized virtual environment and run the notebook.

Notebooks may generate a variety of files during runtime, such as test datasets and figures.

Please feel free to submit an [issue](https://github.com/understanding-search/structured-representations-maze-transformers/issues) if you have any questions, comments, or trouble running the notebooks -- we are happy to help!

# Citing

Please cite this work as:
```bibtex
@misc{ivanitskiy2023swrmt,
	title={Structured World Representations in Maze-Solving Transformers}, 
	author={Michael Igorevich Ivanitskiy and Alex F. Spies and Tilman Räuker and Guillaume Corlouer and Chris Mathwin and Lucia Quirke and Can Rager and Rusheb Shah and Dan Valentine and Cecilia Diniz Behn and Katsumi Inoue and Samy Wu Fung},
	year={2023},
	eprint={2312.02566},
	url={https://arxiv.org/abs/2312.02566},
	archivePrefix={arXiv},
	primaryClass={cs.LG}
}
```