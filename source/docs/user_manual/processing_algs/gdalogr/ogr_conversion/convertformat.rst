Convert format
==============

Description
-----------

<put algortithm description here>

Parameters
----------

``Input layer`` [vector: any]
  <put parameter description here>

``Destination Format`` [selection]
  <put parameter description here>

  Options:

  * 0 --- ESRI Shapefile
  * 1 --- GeoJSON
  * 2 --- GeoRSS
  * 3 --- SQLite
  * 4 --- GMT
  * 5 --- MapInfo File
  * 6 --- INTERLIS 1
  * 7 --- INTERLIS 2
  * 8 --- GML
  * 9 --- Geoconcept
  * 10 --- DXF
  * 11 --- DGN
  * 12 --- CSV
  * 13 --- BNA
  * 14 --- S57
  * 15 --- KML
  * 16 --- GPX
  * 17 --- PGDump
  * 18 --- GPSTrackMaker
  * 19 --- ODS
  * 20 --- XLSX
  * 21 --- PDF

  Default: *0*

``Creation Options`` [string]
  Optional.

  <put parameter description here>

  Default: *(not set)*

Outputs
-------

``Output layer`` [vector]
  <put output description here>

Console usage
-------------

::

  processing.runalg('gdalogr:convertformat', input_layer, format, options, output_layer)

See also
--------

