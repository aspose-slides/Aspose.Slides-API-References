---
title: ShapeElement
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje część kształtu o tych samych właściwościach konturu i wypełnienia.
type: docs
url: /pl/com.aspose.slides/shapeelement/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Reprezentuje część kształtu z tymi samymi właściwościami konturu i wypełnienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParentShape()](#getParentShape--) | Zwraca Shape_PPT, dla którego element został utworzony. |
| [getPathPoints()](#getPathPoints--) | Zwraca tablicę punktów, które definiują geometrię ścieżki elementu. |
| [getPathTypes()](#getPathTypes--) | Zwraca tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu. |
| [getFillSource()](#getFillSource--) | Zwraca informacje o sposobie wypełniania elementu. |
| [getStrokeSource()](#getStrokeSource--) | Zwraca informacje o sposobie obrysowywania elementu. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Zwraca Shape_PPT, dla którego element został utworzony. Tylko do odczytu [Shape](../../com.aspose.slides/shape).

**Zwraca:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final Point2D.Float[] getPathPoints()
```

Zwraca tablicę punktów definiujących geometrię ścieżki elementu.

**Zwraca:**
java.awt.geom.Point2D.Float[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Zwraca tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.

**0** Oznacza, że punkt jest początkiem figury.

**1** Oznacza, że punkt jest jednym z dwóch końcowych punktów linii.

**3** Oznacza, że punkt jest końcowym lub kontrolnym punktem sześciennej krzywej Beziera.

**7** Maskuje wszystkie bity oprócz trzech bitów najmniej znaczących, które określają typ punktu.

**16** Określa, że odpowiadający segment jest przerywany.

**32** Określa, że punkt jest znacznikiem.

**128** Określa, że punkt jest ostatnim punktem w zamkniętej podścieżce (figurze).

**129** Oznacza punkt danych będący zarówno końcowym punktem segmentu linii, jak i ostatnim punktem zamkniętej podścieżki.

**Zwraca:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Zwraca informacje o sposobie wypełniania elementu. Tylko do odczytu [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Zwraca:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Zwraca informacje o sposobie obrysowywania elementu. Tylko do odczytu [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Zwraca:**
byte