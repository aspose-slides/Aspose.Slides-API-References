---
title: ShapeElement
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Teil einer Form mit denselben Umriss- und Füll-Eigenschaften dar.
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

Stellt einen Teil einer Form mit denselben Umriss- und Füll-Eigenschaften dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParentShape()](#getParentShape--) | Gibt ein Shape_PPT zurück, für das das Element erstellt wurde. |
| [getPathPoints()](#getPathPoints--) | Gibt ein Array von Punkten zurück, das die Geometrie des Pfads des Elements definiert. |
| [getPathTypes()](#getPathTypes--) | Gibt ein Array von Byte-Werten zurück, das den Typ jedes Punkts im Pfad des Elements angibt. |
| [getFillSource()](#getFillSource--) | Gibt Informationen darüber zurück, wie ein Element gefüllt wird. |
| [getStrokeSource()](#getStrokeSource--) | Gibt Informationen darüber zurück, wie ein Element konturiert wird. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```


Gibt ein Shape_PPT zurück, für das das Element erstellt wurde. Nur lesbar [Shape](../../com.aspose.slides/shape).

**Rückgabe:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```


Gibt ein Array von Punkten zurück, das die Geometrie des Pfads des Elements definiert.

**Rückgabe:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```


Gibt ein Array von Byte-Werten zurück, das den Typ jedes Punkts im Pfad des Elements angibt.

**0** Gibt an, dass der Punkt der Anfang einer Figur ist.

**1** Gibt an, dass der Punkt einer der beiden Endpunkte einer Linie ist.

**3** Gibt an, dass der Punkt ein End- oder Kontrollpunkt einer kubischen Bézier-Kurve ist.

**7** Maskiert alle Bits außer den drei niederwertigen Bits, die den Punkt-Typ angeben.

**16** Gibt an, dass das entsprechende Segment gestrichelt ist.

**32** Gibt an, dass der Punkt ein Marker ist.

**128** Gibt an, dass der Punkt der letzte Punkt in einem geschlossenen Unterpfad (Figur) ist.

**129** Gibt einen Datenpunkt an, der sowohl Endpunkt eines Liniensegments als auch letzter Punkt eines geschlossenen Unterpfads ist.

**Rückgabe:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```


Gibt Informationen darüber zurück, wie ein Element gefüllt wird. Nur lesbar [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Rückgabe:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```


Gibt Informationen darüber zurück, wie ein Element konturiert wird. Nur lesbar [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Rückgabe:**
byte