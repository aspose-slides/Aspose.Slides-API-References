---
title: ShapeFrame
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Eigenschaften des Formrahmens dar.
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

Stellt die Eigenschaften des Formrahmens dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Erstellt neue Eigenschaften des Formrahmens. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Gibt die X-Koordinate der linken oberen Ecke eines Rahmens zurück. |
| [getY()](#getY--) | Gibt die Y-Koordinate der linken oberen Ecke eines Rahmens zurück. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Rahmens zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Rahmens zurück. |
| [getRotation()](#getRotation--) | Gibt die Anzahl der Grad zurück, um die ein Rahmen um die Z-Achse gedreht ist. |
| [getCenterX()](#getCenterX--) | Gibt die X-Koordinate des Zentrums eines Rahmens zurück. |
| [getCenterY()](#getCenterY--) | Gibt die Y-Koordinate des Zentrums eines Rahmens zurück. |
| [getFlipH()](#getFlipH--) | Bestimmt, ob ein Rahmen horizontal gespiegelt ist. |
| [getFlipV()](#getFlipV--) | Bestimmt, ob ein Rahmen vertikal gespiegelt ist. |
| [getRectangle()](#getRectangle--) | Gibt die Koordinaten eines Rahmens zurück. |
| [deepClone()](#deepClone--) | Kopiert |
| [cloneT()](#cloneT--) | Kopiert. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht. |

### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Erstellt neue Eigenschaften des Formrahmens.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate eines Rahmens. |
| y | float | Y-Koordinate eines Rahmens. |
| width | float | Breite eines Rahmens. |
| height | float | Höhe eines Rahmens. |
| flipH | byte | Wahr, wenn ein Rahmen horizontal gespiegelt ist. |
| flipV | byte | Wahr, wenn ein Rahmen vertikal gespiegelt ist. |
| rotationAngle | float | Anzahl der Grad, um die ein Rahmen gedreht ist. |

### getX() {#getX--}
```
public final float getX()
```

Gibt die X-Koordinate der linken oberen Ecke eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getY() {#getY--}
```
public final float getY()
```

Gibt die Y-Koordinate der linken oberen Ecke eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gibt die Breite eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gibt die Höhe eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Gibt die Anzahl der Grad zurück, um die ein Rahmen um die Z-Achse gedreht ist. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Nur lesbar float.

**Rückgabewert:**
float

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Gibt die X-Koordinate des Zentrums eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Gibt die Y-Koordinate des Zentrums eines Rahmens zurück. Nur lesbar float.

**Rückgabewert:**
float

### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Bestimmt, ob ein Rahmen horizontal gespiegelt ist. Nur lesbar [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Bestimmt, ob ein Rahmen vertikal gespiegelt ist. Nur lesbar [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Gibt die Koordinaten eines Rahmens zurück. Nur lesbar java.awt.geom.Rectangle2D.Float.

**Rückgabewert:**
java.awt.geom.Rectangle2D.Float

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Kopiert

**Rückgabewert:**
java.lang.Object - Kopierter Formrahmen.

### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Kopiert.

**Rückgabewert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Kopierter Formrahmen.

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Rückgabewert:**
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

**Rückgabewert:**
boolean - **true**, wenn obj ein ShapeFrame ist, das denselben Wert wie diese Instanz hat; andernfalls **false**.

### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen Objekt entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Der ShapeFRameEx, der mit dieser Instanz verglichen wird. |

**Rückgabewert:**
boolean - **true**, wenn value ein ShapeFrame ist, das denselben Wert wie diese Instanz hat; andernfalls **false**.