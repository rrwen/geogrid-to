# geogrid-to

* [Latest Release](https://github.com/rrwen/geogrid-to/releases/tag/v1.0)
* [Developer Notes](DEVELOPER.md)

A geospatial dataset of over 1000+ spatially aggregated variables by various grid sizes for Toronto, Ontario, Canada - primarily from city and police open data.

## Usage

The dataset is available as:

* One large `.geojson` file
* Several `.geojson` files separated by several source datasets
* Several `.csv` files of each variable that can be joined to grids to create a custom geospatial dataset

Go to the [releases page](https://github.com/rrwen/geogrid-to/releases) for download options.

## Details

* The raw data sources are listed in [data.csv](src/data.csv)
* The entire process to generate the dataset is documented in three notebooks:
    1. [src/download.ipynb](src/download.ipynb): code/notes for downloading raw data
    2. [src/preprocess.ipynb](src/preprocess.ipynb): code/notes for preprocessing raw data
    3. [src/run.ipynb](src/run.ipynb): code/notes for generating the final datasets

See [DEVELOPER.md](DEVELOPER.md) for more details on how to reproduce the dataset.

## Contact

Richard Wen <rrwen.dev@gmail.com>
