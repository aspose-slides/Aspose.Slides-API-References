---
title: get_PathTypes()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert een array van bytewaarden die het type van elk punt in het pad van het element specificeert.
type: docs
weight: 27
url: /nl/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() methode

Retourneert een array van bytewaarden die het type van elk punt in het pad van het element specificeert.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Opmerkingen

**0** Geeft aan dat het punt het begin van een figuur is.

**1** Geeft aan dat het punt een van de twee eindpunten van een lijn is.

**3** Geeft aan dat het punt een eindpunt of controlepunt van een kubieke Bezier-spline is.

**7** Maskeert alle bits behalve de drie laagste bits, die het punttype aangeven.

**16** Geeft aan dat het corresponderende segment gestippeld is.

**32** Geeft aan dat het punt een markering is.

**128** Geeft aan dat het punt het laatste punt in een gesloten subpad (figuur) is.

**129** Geeft een datumpunt aan dat zowel een eindpunt van een lijnsegment als het laatste punt van een gesloten subpad is.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ShapeElement](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)