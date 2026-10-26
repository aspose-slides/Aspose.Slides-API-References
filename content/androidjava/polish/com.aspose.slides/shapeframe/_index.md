---
title: ShapeFrame
second_title: Aspose.Slides dla Androida – Referencja API Java
description: Reprezentuje właściwości ramki kształtu.
type: docs
url: /pl/com.aspose.slides/shapeframe/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Reprezentuje właściwości ramki kształtu.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Tworzy nowe właściwości ramki kształtu. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getX()](#getX--) | Zwraca współrzędną X lewego górnego rogu ramki. |
| [getY()](#getY--) | Zwraca współrzędną Y lewego górnego rogu ramki. |
| [getWidth()](#getWidth--) | Zwraca szerokość ramki. |
| [getHeight()](#getHeight--) | Zwraca wysokość ramki. |
| [getRotation()](#getRotation--) | Zwraca liczbę stopni, o którą ramka jest obrócona wokół osi Z. |
| [getCenterX()](#getCenterX--) | Zwraca współrzędną X środka ramki. |
| [getCenterY()](#getCenterY--) | Zwraca współrzędną Y środka ramki. |
| [getFlipH()](#getFlipH--) | Określa, czy ramka jest odbita w poziomie. |
| [getFlipV()](#getFlipV--) | Określa, czy ramka jest odbita w pionie. |
| [getRectangle()](#getRectangle--) | Zwraca współrzędne ramki. |
| [deepClone()](#deepClone--) | Klonuje |
| [cloneT()](#cloneT--) | Klonuje. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Zwraca wartość wskazującą, czy ta instancja jest równa określonemu obiektowi. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Zwraca wartość wskazującą, czy ta instancja jest równa określonemu obiektowi. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Tworzy nowe właściwości ramki kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X ramki. |
| y | float | Współrzędna Y ramki. |
| width | float | Szerokość ramki. |
| height | float | Wysokość ramki. |
| flipH | byte | Prawda, jeśli ramka jest odbita w poziomie. |
| flipV | byte | Prawda, jeśli ramka jest odbita w pionie. |
| rotationAngle | float | Liczba stopni, o które ramka jest obrócona. |

### getX() {#getX--}
```
public final float getX()
```


Zwraca współrzędną X lewego górnego rogu ramki. Tylko do odczytu float.

**Zwraca:**
float
### getY() {#getY--}
```
public final float getY()
```


Zwraca współrzędną Y lewego górnego rogu ramki. Tylko do odczytu float.

**Zwraca:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Zwraca szerokość ramki. Tylko do odczytu float.

**Zwraca:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Zwraca wysokość ramki. Tylko do odczytu float.

**Zwraca:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Zwraca liczbę stopni, o którą ramka jest obrócona wokół osi Z. Wartość dodatnia wskazuje obrót zgodny z ruchem wskazówek zegara; wartość ujemna wskazuje obrót przeciwny do ruchu wskazówek zegara. Tylko do odczytu float.

**Zwraca:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Zwraca współrzędną X środka ramki. Tylko do odczytu float.

**Zwraca:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Zwraca współrzędną Y środka ramki. Tylko do odczytu float.

**Zwraca:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Określa, czy ramka jest odbita w poziomie. Tylko do odczytu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Określa, czy ramka jest odbita w pionie. Tylko do odczytu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Zwraca współrzędne ramki. Tylko do odczytu android.graphics.RectF.

**Zwraca:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klonuje

**Zwraca:**
java.lang.Object - Zklonowana ramka kształtu.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Klonuje.

**Zwraca:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Zklonowana ramka kształtu.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Zwraca:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Zwraca wartość wskazującą, czy ta instancja jest równa określonemu obiektowi.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt, z którym porównywana jest ta instancja. |

**Zwraca:**
boolean - **true**, jeśli obj jest ShapeFrame, który ma taką samą wartość jak ta instancja; w przeciwnym razie **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Zwraca wartość wskazującą, czy ta instancja jest równa określonemu obiektowi.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx do porównania z tą instancją. |

**Zwraca:**
boolean - **true**, jeśli value jest ShapeFrame, który ma taką samą wartość jak ta instancja; w przeciwnym razie **false**.