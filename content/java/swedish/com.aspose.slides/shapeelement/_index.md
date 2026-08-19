---
title: ShapeElement
second_title: Aspose.Slides för Java API-referens
description: Representerar en del av en form med samma kontur- och fyllningsegenskaper.
type: docs
url: /sv/com.aspose.slides/shapeelement/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Representerar en del av en form med samma kontur- och fyllningsegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParentShape()](#getParentShape--) | Returnerar en Shape_PPT för vilken element skapades. |
| [getPathPoints()](#getPathPoints--) | Hämtar en array av punkter som definierar geometrin för elementets bana. |
| [getPathTypes()](#getPathTypes--) | Hämtar en array av byte-värden som specificerar typen för varje punkt i elementets bana. |
| [getFillSource()](#getFillSource--) | Returnerar information om hur ett element ska fyllas. |
| [getStrokeSource()](#getStrokeSource--) | Returnerar information om hur ett element ska kontureras. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Returnerar en Shape_PPT för vilken element skapades. Skrivskyddad [Shape](../../com.aspose.slides/shape).

**Returnerar:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```


Hämtar en array av punkter som definierar geometrin för elementets bana.

**Returnerar:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Hämtar en array av byte-värden som specificerar typen för varje punkt i elementets bana.

**0** Anger att punkten är början på en figur.

**1** Anger att punkten är en av de två ändpunkterna på en linje.

**3** Anger att punkten är en slutpunkt eller kontrollpunkt för en kubisk Bézier-spline.

**7** Maskerar alla bitar förutom de tre lägsta, som anger punktens typ.

**16** Specificerar att motsvarande segment är streckat.

**32** Specificerar att punkten är en markör.

**128** Specificerar att punkten är den sista punkten i en sluten delbana (figur).

**129** Anger en datapunkt som både är en linjesegment-ändpunkt och den sista punkten i en sluten delbana.

**Returnerar:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Returnerar information om hur ett element ska fyllas. Skrivskyddad [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Returnerar:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Returnerar information om hur ett element ska kontureras. Skrivskyddad [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Returnerar:**
byte