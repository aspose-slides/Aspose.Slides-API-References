---
title: ShapeElement
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een deel van een vorm met dezelfde omtrek- en vul-eigenschappen.
type: docs
url: /nl/com.aspose.slides/shapeelement/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Stelt een deel van een vorm voor met dezelfde omtrek- en vul-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParentShape()](#getParentShape--) | Geeft een Shape_PPT terug waarvoor het element is gemaakt. |
| [getPathPoints()](#getPathPoints--) | Haalt een array met punten op die de geometrie van het pad van het element definiëren. |
| [getPathTypes()](#getPathTypes--) | Haalt een array met byte-waarden op die het type van elk punt in het pad van het element aangeven. |
| [getFillSource()](#getFillSource--) | Geeft informatie over hoe een element moet worden gevuld. |
| [getStrokeSource()](#getStrokeSource--) | Geeft informatie over hoe een element moet worden omrand. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Geeft een Shape_PPT terug waarvoor het element is gemaakt. Alleen-lezen [Shape](../../com.aspose.slides/shape).

**Retour:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Haalt een array met punten op die de geometrie van het pad van het element definiëren.

**Retour:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Haalt een array met byte-waarden op die het type van elk punt in het pad van het element aangeven.

**0** Geeft aan dat het punt het begin van een figuur is.

**1** Geeft aan dat het punt een van de twee eindpunten van een lijn is.

**3** Geeft aan dat het punt een eindpunt of controlepunt van een kubieke Bezier-spline is.

**7** Maskeert alle bits behalve de drie laagste bits, die het punt-type aangeven.

**16** Geeft aan dat het overeenkomstige segment gestreept is.

**32** Geeft aan dat het punt een markering is.

**128** Geeft aan dat het punt het laatste punt in een gesloten subpad (figuur) is.

**129** Geeft een datapunt aan dat zowel een eindpunt van een lijnsegment als het laatste punt van een gesloten subpad is.

**Retour:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Geeft informatie over hoe een element moet worden gevuld. Alleen-lezen [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Retour:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Geeft informatie over hoe een element moet worden omrand. Alleen-lezen [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Retour:**
byte