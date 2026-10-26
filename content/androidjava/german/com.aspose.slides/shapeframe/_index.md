---
title: ShapeFrame
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt die Eigenschaften von ShapeFrames dar.
type: docs
url: /de/com.aspose.slides/shapeframe/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Stellt die Eigenschaften des ShapeFrames dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Erstellt neue Eigenschaften des ShapeFrames. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Gibt die X-Koordinate der oberen linken Ecke eines Frames zurück. |
| [getY()](#getY--) | Gibt die Y-Koordinate der oberen linken Ecke eines Frames zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Frames zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Frames zurück. |
| [getRotation()](#getRotation--) | Gibt die Anzahl der Grad zurück, um die ein Frame um die Z-Achse gedreht ist. |
| [getCenterX()](#getCenterX--) | Gibt die X-Koordinate des Zentrums eines Frames zurück. |
| [getCenterY()](#getCenterY--) | Gibt die Y-Koordinate des Zentrums eines Frames zurück. |
| [getFlipH()](#getFlipH--) | Bestimmt, ob ein Frame horizontal gespiegelt ist. |
| [getFlipV()](#getFlipV--) | Bestimmt, ob ein Frame vertikal gespiegelt ist. |
| [getRectangle()](#getRectangle--) | Gibt die Koordinaten eines Frames zurück. |
| [deepClone()](#deepClone--) | Klont |
| [cloneT()](#cloneT--) | Klont. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Erstellt neue Eigenschaften des ShapeFrames.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate eines Frames. |
| y | float | Y-Koordinate eines Frames. |
| width | float | Breite eines Frames. |
| height | float | Höhe eines Frames. |
| flipH | byte | Wahr, wenn ein Frame horizontal gespiegelt ist. |
| flipV | byte | Wahr, wenn ein Frame vertikal gespiegelt ist. |
| rotationAngle | float | Anzahl der Grad, um die ein Frame gedreht ist. |

### getX() {#getX--}
```
public final float getX()
```


Gibt die X-Koordinate der oberen linken Ecke eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getY() {#getY--}
```
public final float getY()
```


Gibt die Y-Koordinate der oberen linken Ecke eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Gibt die Breite eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Gibt die Höhe eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Gibt die Anzahl der Grad zurück, um die ein Frame um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Nur lesbar float.

**Rückgabe:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Gibt die X-Koordinate des Zentrums eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Gibt die Y-Koordinate des Zentrums eines Frames zurück. Nur lesbar float.

**Rückgabe:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Bestimmt, ob ein Frame horizontal gespiegelt ist. Nur lesbar [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Bestimmt, ob ein Frame vertikal gespiegelt ist. Nur lesbar [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Gibt die Koordinaten eines Frames zurück. Nur lesbar android.graphics.RectF.

**Rückgabe:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klont

**Rückgabe:**
java.lang.Object - Klonierter ShapeFrame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Klont.

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klonierter ShapeFrame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Rückgabe:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, das mit dieser Instanz verglichen wird. |

**Rückgabe:**
boolean - **true**, wenn obj ein ShapeFrame ist, das den gleichen Wert wie diese Instanz hat; andernfalls **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Der ShapeFRameEx, der mit dieser Instanz verglichen wird. |

**Rückgabe:**
boolean - **true**, wenn value ein ShapeFrame ist, das den gleichen Wert wie diese Instanz hat; andernfalls **false**.