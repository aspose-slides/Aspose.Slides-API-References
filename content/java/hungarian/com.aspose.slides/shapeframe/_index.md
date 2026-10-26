---
title: ShapeFrame
second_title: Aspose.Slides Java API Referencia
description: A shape frame tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/shapeframe/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

A shape frame tulajdonságait képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Új shape frame tulajdonságait hoz létre. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getX()](#getX--) | Visszaadja egy keret bal felső sarkának X koordinátáját. |
| [getY()](#getY--) | Visszaadja egy keret bal felső sarkának Y koordinátáját. |
| [getWidth()](#getWidth--) | Visszaadja egy keret szélességét. |
| [getHeight()](#getHeight--) | Visszaadja egy keret magasságát. |
| [getRotation()](#getRotation--) | Visszaadja a keret z-tengely körül forgatott fokszámát. |
| [getCenterX()](#getCenterX--) | Visszaadja egy keret középpontjának X koordinátáját. |
| [getCenterY()](#getCenterY--) | Visszaadja egy keret középpontjának Y koordinátáját. |
| [getFlipH()](#getFlipH--) | Megállapítja, hogy a keret vízszintesen tükrözött-e. |
| [getFlipV()](#getFlipV--) | Megállapítja, hogy a keret függőlegesen tükrözött-e. |
| [getRectangle()](#getRectangle--) | Visszaadja egy keret koordinátáit. |
| [deepClone()](#deepClone--) | Másolatot készít |
| [cloneT()](#cloneT--) | Másolatot készít. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Visszaad egy értéket, amely jelzi, hogy ez a példány egy megadott objektummal egyenlő-e. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Visszaad egy értéket, amely jelzi, hogy ez a példány egy megadott objektummal egyenlő-e. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

Új shape frame tulajdonságait hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | Keret X koordinátája. |
| y | float | Keret Y koordinátája. |
| width | float | Keret szélessége. |
| height | float | Keret magassága. |
| flipH | byte | Igaz, ha a keret vízszintesen tükrözött. |
| flipV | byte | Igaz, ha a keret függőlegesen tükrözött. |
| rotationAngle | float | A keret forgatásának fokszáma. |

### getX() {#getX--}
```
public final float getX()
```

Visszaadja egy keret bal felső sarkának X koordinátáját. **Csak olvasható** float.

**Visszatérési érték:**
float
### getY() {#getY--}
```
public final float getY()
```

Visszaadja egy keret bal felső sarkának Y koordinátáját. **Csak olvasható** float.

**Visszatérési érték:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Visszaadja egy keret szélességét. **Csak olvasható** float.

**Visszatérési érték:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Visszaadja egy keret magasságát. **Csak olvasható** float.

**Visszatérési érték:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Visszaadja a keret z-tengely körül forgatott fokszámát. Pozitív érték óramutató járásával megegyező forgatást jelez; negatív érték ellentétes irányt. **Csak olvasható** float.

**Visszatérési érték:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

Visszaadja egy keret középpontjának X koordinátáját. **Csak olvasható** float.

**Visszatérési érték:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

Visszaadja egy keret középpontjának Y koordinátáját. **Csak olvasható** float.

**Visszatérési érték:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

Megállapítja, hogy a keret vízszintesen tükrözött-e. **Csak olvasható** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

Megállapítja, hogy a keret függőlegesen tükrözött-e. **Csak olvasható** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Visszaadja egy keret koordinátáit. **Csak olvasható** java.awt.geom.Rectangle2D.Float.

**Visszatérési érték:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Másolatot készít

**Visszatérési érték:**
java.lang.Object - Klónozott shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

Másolatot készít.

**Visszatérési érték:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klónozott shape frame.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Visszatérési érték:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Visszaad egy értéket, amely jelzi, hogy ez a példány egy megadott objektummal egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az objektum, amelyet összehasonlítunk ezzel a példánnyal. |

**Visszatérési érték:**
boolean - **true**, ha az obj egy ShapeFrame, amelynek értéke megegyezik ezzel a példánnyal; egyébként **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

Visszaad egy értéket, amely jelzi, hogy ez a példány egy megadott objektummal egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | A ShapeFRameEx, amelyet összehasonlítunk ezzel a példánnyal. |

**Visszatérési érték:**
boolean - **true**, ha a value egy ShapeFrame, amelynek értéke megegyezik ezzel a példánnyal; egyébként **false**.