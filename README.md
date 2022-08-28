# Analyse der Entwicklung der Gebäudehöhen der Stadt Zürich

**Artikel**: ["Hier schiesst Zürich in die Höhe"](https://www.tagesanzeiger.ch/hier-schiesst-zuerich-in-die-hoehe-336605433294), Tagesanzeiger 18. September 2020

**Quick-Access**: 
* [Aufbereitung: R-Markdown](3D_Zurich_Aufbereitung.Rmd)
* [Analyse: R-Markdown](3D_Zurich_Analyse_github.Rmd)
* [HTML-Darstellung der Analyse](https://interaktiv.tagesanzeiger.ch//2020/daten_Zurich3D/3D_Zurich_Analyse_github.html)
* [HTML-File auf Github](3D_Zurich_Analyse_github.html)


## Datengrundlage
Die Stadt Zürich publiziert im 2 Wochenrythmus alle Gebäudeumrisse und Gebäudehöhen als Open Data. Historisch sind die Daten jährlich ab 2012 verfügbar:
https://data.stadt-zuerich.ch/dataset/geo_3d_blockmodell_lod1

Die Umrisse der statistischen Quartiere gibt es ebenfalls als Open Data:
https://data.stadt-zuerich.ch/dataset/geo_statistische_quartiere

Die Daten sind nicht in diesem Repository hinterlegt, aber können mit den oben gennanten Links heruntergeladen werden.

## Analyse
Der erste Schritt ist die Aufbereitung der Daten in einem [eigenen Script](3D_Zurich_Aufbereitung.Rmd). Hier werden zu allen Gebäudegrundrissen als zusätzliches Attribut der Kreis und das Quartier hinterlegt. Der Output wird als Geojeson gespeichert und kann dann mit dem Analyse Script eingelesen werden.

Die gesamte Analyse findet sich im hinterlegten R-Markdown file: [3D_Zurich_Analyse_github.Rmd](3D_Zurich_Analyse_github.Rmd)

Oder sauber lesbar inklusive Resultate und Visualisierung als [html file](https://interaktiv.tagesanzeiger.ch/2020/daten_Zurich3D/3D_Zurich_Analyse_github.html) (Gehostet auf Tagesanzeiger Server.)
