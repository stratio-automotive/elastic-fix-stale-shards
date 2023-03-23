# Elastic Fix Stale Shards

Elastic Fix Stale Shards is a .NET interactive notebook that helps Elasticsearch administrators to fix stale shards. It is very helpful when you have a lot of indices and a lot of nodes.

## Requirements

* [Visual Studio Code](https://code.visualstudio.com/)
* [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)

## Installation

1. Clone this repository: `git clone https://github.com/stratio-automotive/elastic-fix-stale-shards.git`
2. Open the notebook [`fix_stale_shards.ipynb`](https://github.com/stratio-automotive/elastic-fix-stale-shards/blob/main/elasticsearch_fix_stale_shards.ipynb).

## Usage

1. Edit the configuration cell in the notebook with your Elasticsearch cluster settings.
2. Run the notebook.

## How it works

The notebook uses the Elasticsearch .NET API to check the status of the shards and fix the stale ones by relocating them to a new node.

## Warning

This notebook should be used with caution, as it modifies the state of the Elasticsearch cluster and could cause data loss. Always backup your data before running it.

## Contributing

We welcome contributions! If you find a bug or have a feature request, please open an issue. If you want to contribute code, please fork the repository and submit a pull request.

## License

Elastic Fix Stale Shards is licensed under the MIT License. See the [LICENSE file](https://github.com/stratio-automotive/elastic-fix-stale-shards/blob/main/LICENSE) for more information.

## Contact

If you have any questions or comments about this notebook, please contact the Stratio team at [it@stratioautomotive.com](mailto:it@stratioautomotive.com).
