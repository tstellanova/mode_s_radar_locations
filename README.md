Mode-S radar locations
======================

This is a shared, open directory of air traffic control radars around
the world, focusing on stations with [Mode-S secondary surveillance
radars](http://en.wikipedia.org/wiki/Aviation_transponder_interrogation_modes#Mode_S).

To view the map, you can view the [stations.geojson](stations.geojson)
file.

Coordinates
-----------

The latitude, longitude and elevation (in feet) of each station are given.

Properties
----------

Each station may have the following properties:

|Property |Required?|Description                             |
|---------|---------|----------------------------------------|
|mode_s   |Yes      |True if confirmed Mode S.               |
|name     |No       |String.                                 |
|range    |No       |String. Range of radar.                 |
|source   |No       |String. Provenance of this information. |
|comments |No       |Array of strings. Additional comments.  |

Updates, corrections, additions
-------------------------------

To add a new station, add additional information to an existing
station or correct mistakes in this data, [send a pull
request](https://help.github.com/articles/using-pull-requests).
