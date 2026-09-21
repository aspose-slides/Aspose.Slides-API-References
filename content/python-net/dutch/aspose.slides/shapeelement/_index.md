---
title: ShapeElement class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapeelement/
---
## ShapeElement klasse

Stelt een deel van een vorm voor met dezelfde contour- en vul-eigenschappen.

Het type ShapeElement biedt de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`parent_shape`](/slides/python-net/nl/aspose.slides/shapeelement/parent_shape/) | Retourneert een Shape_PPT waarvoor het element is gemaakt.<br/>            Alleen-lezen [`Shape`](/slides/python-net/nl/aspose.slides/shape). |
| [`path_points`](/slides/python-net/nl/aspose.slides/shapeelement/path_points/) | Haalt een array van punten op die de geometrie van het pad van het element definiëren. |
| [`path_types`](/slides/python-net/nl/aspose.slides/shapeelement/path_types/) | Haalt een array van byte-waarden op die het type van elk punt in het pad van het element specificeren. <br/>            <br/>**0**  Geeft aan dat het punt het begin van een figuur is.<br/><br/><br/>**1**  Geeft aan dat het punt een van de twee eindpunten van een lijn is.<br/><br/><br/>**3**  Geeft aan dat het punt een eindpunt of controlepunt is van een kubieke Bezier-spline.<br/><br/><br/>**7**  Maskeert alle bits behalve de drie laagste bits, die het punttype aangeven.<br/><br/><br/>**16**  Geeft aan dat het overeenkomstige segment gestippeld is.<br/><br/><br/>**32**  Geeft aan dat het punt een marker is.<br/><br/><br/>**128**  Geeft aan dat het punt het laatste punt is in een gesloten subpad (figuur).<br/><br/><br/>**129**  Geeft een datapunt aan dat zowel een eindpunt van een lijnsegment als het laatste punt van een gesloten subpad is. |
| [`fill_source`](/slides/python-net/nl/aspose.slides/shapeelement/fill_source/) | Retourneert informatie over hoe een element te vullen.<br/>            Alleen-lezen [`ShapeElementFillSource`](/slides/python-net/nl/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/nl/aspose.slides/shapeelement/stroke_source/) | Retourneert informatie over hoe een element te tekenen.<br/>            Alleen-lezen [`ShapeElementStrokeSource`](/slides/python-net/nl/aspose.slides/shapeelementstrokesource). |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)