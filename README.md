# PathogenDB visualization

## Requirements

Apache and PHP. Could be readily hosted in a [Minerva](http://hpc.mssm.edu/) www directory.

## Usage

1. Clone this repository into a web-accessible directory
2. Supply analysis output from [pathogendb-comparison][] by placing it in `data/`.
3. Access any of the `.php` files via a web browser. (for now, this is only `heatmap.php`)

[pathogendb-comparison]: https://github.com/powerpak/pathogendb-comparison

### Optional configuration

1. Copy `php/example.include.php` to `php/include.php` and edit the stubs to include extra HTML, CSS, or JS in the visualizations. This could be used to theme the pages or integrate them into another website.
2. Copy `js/example.config.js` to `js/config.js` and edit the variables there to change link destinations and other properties of the visualizations.

## Visualizations

### heatmap

Visualizes the output of [pathogendb-comparison][]'s heatmap task.

TODO: explain further here.