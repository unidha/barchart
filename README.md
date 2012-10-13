This stacked bar chart is constructed from a CSV file storing the populations of different states by age group. The chart employs [conventional margins](http://bl.ocks.org/3019563) and a number of D3 features:

* [d3.csv](https://github.com/mbostock/d3/wiki/CSV) - load and parse data
* [d3.scale.ordinal](https://github.com/mbostock/d3/wiki/Ordinal-Scales) - *x*-position encoding
* [d3.scale.linear](https://github.com/mbostock/d3/wiki/Quantitative-Scales) - *y*-position encoding
* [d3.max](https://github.com/mbostock/d3/wiki/Arrays#wiki-d3_max) - compute domains
* [d3.svg.axis](https://github.com/mbostock/d3/wiki/SVG-Axes) - display axes
