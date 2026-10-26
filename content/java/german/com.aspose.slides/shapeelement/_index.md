---
title: ShapeElement
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Teil einer Form mit denselben Kontur- und Fülleigenschaften dar.
type: docs
url: /de/com.aspose.slides/shapeelement/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Stellt einen Teil einer Form mit denselben Kontur- und Fülleigenschaften dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParentShape()](#getParentShape--) | Gibt ein Shape_PPT zurück, für das das Element erstellt wurde. |
| [getPathPoints()](#getPathPoints--) | Liefert ein Array von Punkten, das die Geometrie des Pfads des Elements definiert. |
| [getPathTypes()](#getPathTypes--) | Liefert ein Array von Byte-Werten, das den Typ jedes Punktes im Pfad des Elements angibt. |
| [getFillSource()](#getFillSource--) | Gibt Informationen darüber, wie ein Element gefüllt wird. |
| [getStrokeSource()](#getStrokeSource--) | Gibt Informationen darüber, wie ein Element konturiert wird. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Gibt ein Shape_PPT zurück, für das das Element erstellt wurde. Nur lesbar [Shape](../../com.aspose.slides/shape).

**Rückgabe:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Liefert ein Array von Punkten, das die Geometrie des Pfads des Elements definiert.

**Rückgabe:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Liefert ein Array von Byte-Werten, das den Typ jedes Punktes im Pfad des Elements angibt.

**0** Gibt an, dass der Punkt der Anfang einer Figur ist.

**1** Gibt an, dass der Punkt einer der beiden Endpunkte einer Linie ist.

**3** Gibt an, dass der Punkt ein Endpunkt oder ein Steuerpunkt einer kubischen Bézier-Kurve ist.

**7** Maskiert alle Bits außer den drei niederwertigen Bits, die den Punktetyp anzeigen.

**16** Gibt an, dass das entsprechende Segment gestrichelt ist.

**32** Gibt an, dass der Punkt ein Marker ist.

**128** Gibt an, dass der Punkt der letzte Punkt eines geschlossenen Unterpfads (Figur) ist.

**129** Gibt einen Datenpunkt an, der sowohl Endpunkt eines Liniensegments als auch letzter Punkt eines geschlossenen Unterpfads ist.

**Rückgabe:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Gibt Informationen darüber, wie ein Element gefüllt wird. Nur lesbar [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Rückgabe:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Gibt Informationen darüber, wie ein Element konturiert wird. Nur lesbar [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Rückgabe:**
byte