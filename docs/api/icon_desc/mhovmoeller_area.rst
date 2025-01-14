Generates a Hovmoeller diagram data unit for a given geographical area for GRIB (:class:`Fieldset`) input. The generated data can be used to display a two-dimensional graph with latitude or longitude as one axis and time as the other. The average values for each field are taken along the North-South or East-West direction.

The resulting data can be plotted (using a default visualisation and with the plot area based on the range of data values) or saved as a NetCDF data file using :func:`write`.

If access to the computed values is not required, or for more control of the plotting, use :func:`mhovmoellerview`.


.. note::

    See also :func:`mhovmoeller_line`, :func:`mhovmoeller_vertical` and :func:`mhovmoeller_expand`.