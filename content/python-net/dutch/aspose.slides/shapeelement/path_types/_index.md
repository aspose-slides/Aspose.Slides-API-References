---
title: path_types property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types eigenschap
Haalt een array van byte-waarden op die het type van elk punt in het pad van het element specificeren.

**0**  Geeft aan dat het punt het begin van een figuur is.

**1**  Geeft aan dat het punt een van de twee eindpunten van een lijn is.

**3**  Geeft aan dat het punt een eindpunt of controlepunt van een kubieke Bézier-curve is.

**7**  Maskeert alle bits behalve de drie laagste bits, die het punttype aangeven.

**16**  Geeft aan dat het overeenkomstige segment gestreept is.

**32**  Geeft aan dat het punt een marker is.

**128**  Geeft aan dat het punt het laatste punt in een gesloten subpad (figuur) is.

**129**  Geeft een gegevenspunt aan dat zowel een eindpunt van een lijnsegment als het laatste punt van een gesloten subpad is.

### Definitie:
```python
@property
def path_types(self):
    ...
```

### Zie ook
* klasse [`ShapeElement`](/slides/python-net/nl/aspose.slides/shapeelement)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)