---
title: ShapeElement
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje część kształtu o tych samych właściwościach konturu i wypełnienia.
type: docs
url: /pl/com.aspose.slides/shapeelement/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IShapeElement](../../com.aspose.slides/ishapeelement)
```
public class ShapeElement implements IShapeElement
```

Reprezentuje część kształtu o tych samych właściwościach konturu i wypełnienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParentShape()](#getParentShape--) | Zwraca Shape_PPT, dla którego element został utworzony. |
| [getPathPoints()](#getPathPoints--) | Pobiera tablicę punktów definiujących geometrię ścieżki elementu. |
| [getPathTypes()](#getPathTypes--) | Pobiera tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu. |
| [getFillSource()](#getFillSource--) | Zwraca informacje o tym, jak wypełnić element. |
| [getStrokeSource()](#getStrokeSource--) | Zwraca informacje o tym, jak narysować obrys elementu. |
### getParentShape() {#getParentShape--}
```
public final Shape getParentShape()
```

Zwraca Shape_PPT, dla którego element został utworzony. Tylko do odczytu [Shape](../../com.aspose.slides/shape).

**Zwraca:**
[Shape](../../com.aspose.slides/shape)
### getPathPoints() {#getPathPoints--}
```
public final PointF[] getPathPoints()
```

Pobiera tablicę punktów definiujących geometrię ścieżki elementu.

**Zwraca:**
android.graphics.PointF[]
### getPathTypes() {#getPathTypes--}
```
public final byte[] getPathTypes()
```

Pobiera tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.

**0** Wskazuje, że punkt jest początkiem figury.

**1** Wskazuje, że punkt jest jednym z dwóch końcowych punktów linii.

**3** Wskazuje, że punkt jest końcowym lub kontrolnym punktem sześciennej krzywej Béziera.

**7** Maskuje wszystkie bity oprócz trzech najmniej znaczących, które określają typ punktu.

**16** Określa, że odpowiadający segment jest przerywany.

**32** Określa, że punkt jest znacznikiem.

**128** Określa, że punkt jest ostatnim punktem zamkniętej podścieżki (figury).

**129** Wskazuje punkt danych, który jest jednocześnie końcowym punktem segmentu linii i ostatnim punktem zamkniętej podścieżki.

**Zwraca:**
byte[]
### getFillSource() {#getFillSource--}
```
public final byte getFillSource()
```

Zwraca informacje o tym, jak wypełnić element. Tylko do odczytu [ShapeElementFillSource](../../com.aspose.slides/shapeelementfillsource).

**Zwraca:**
byte
### getStrokeSource() {#getStrokeSource--}
```
public final byte getStrokeSource()
```

Zwraca informacje o tym, jak narysować obrys elementu. Tylko do odczytu [ShapeElementStrokeSource](../../com.aspose.slides/shapeelementstrokesource).

**Zwraca:**
byte