#Grünflächen Kataster Köln

Dieser Service liest das Shape-File für das Grünflächekataster von [Gruenflaechenkataster Koeln Flaechentypen](http://offenedaten-koeln.de/dataset/gruenflaechenkataster-koeln-flaechentypen) aus und bietet die so gewonnen Informationen als GeoJson - Information an.

## Ziele

Es soll ein Service erstellt werden, der die von der Stadt Köln zur Verfügung gestellten Informationen bzgl. der Grünflächen als GeoJson formatiert. Desweiteren soll es möglich sein, aufgrund der Art der Grünfläche, Subsets abfragen zu können. Hierfür werden REST-Endpoints eingerichtet. Außerdem soll eine einfache Oberfläche den Inhalt der Services darstellen. Diese Oberfläche soll auf Basis von [BootLeaf](https://github.com/bmcbride/bootleaf) erstellt werden.

## GeoTools

Zur Interpretation der Shape-Dateien wird das Projekt [GeoTools](http://geotools.org/) verwendet (vgl. auch [GeoTools Quickstart](http://docs.geotools.org/latest/userguide/tutorial/index.html))

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />Dieses Werk ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz</a>.
