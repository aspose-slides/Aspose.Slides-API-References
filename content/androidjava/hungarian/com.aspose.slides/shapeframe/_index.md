---
title: ShapeFrame
second_title: Aspose.Slides Android számára Java API referencia
description: A shape frame tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/shapeframe/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

A shape frame tulajdonságait reprezentálja.
## Constructors

| Constructor | Description |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Új shape frame tulajdonságait hoz létre. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | Visszaadja a keret bal felső sarkának X koordinátáját. |
| [getY()](#getY--) | Visszaadja a keret bal felső sarkának Y koordinátáját. |
| [getWidth()](#getWidth--) | Visszaadja a keret szélességét. |
| [getHeight()](#getHeight--) | Visszaadja a keret magasságát. |
| [getRotation()](#getRotation--) | Visszaadja a keret Z tengely körüli elforgatásának fokszámát. |
| [getCenterX()](#getCenterX--) | Visszaadja a keret középpontjának X koordinátáját. |
| [getCenterY()](#getCenterY--) | Visszaadja a keret középpontjának Y koordinátáját. |
| [getFlipH()](#getFlipH--) | Megállapítja, hogy a keret vízszintesen tükrözött-e. |
| [getFlipV()](#getFlipV--) | Megállapítja, hogy a keret függőlegesen tükrözött-e. |
| [getRectangle()](#getRectangle--) | Visszaadja a keret koordinátáit. |
| [deepClone()](#deepClone--) | Klónozza |
| [cloneT()](#cloneT--) | Klónozza. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Visszaad egy értéket, amely azt jelzi, hogy ez a példány egy megadott objektummal egyenlő-e. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Visszaad egy értéket, amely azt jelzi, hogy ez a példány egy megadott objektummal egyenlő-e. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Új shape frame tulajdonságait hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A keret X koordinátája. |
| y | float | A keret Y koordinátája. |
| width | float | A keret szélessége. |
| height | float | A keret magassága. |
| flipH | byte | Igaz, ha a keret vízszintesen tükrözött. |
| flipV | byte | Igaz, ha a keret függőlegesen tükrözött. |
| rotationAngle | float | A keret elforgatásának fokszáma. |

### getX() {#getX--}
```
public final float getX()
```


Visszaadja a keret bal felső sarkának X koordinátáját. Csak olvasható float.

**Visszatérési érték:**
float
### getY() {#getY--}
```
public final float getY()
```


Visszaadja a keret bal felső sarkának Y koordinátáját. Csak olvasható float.

**Visszatérési érték:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Visszaadja a keret szélességét. Csak olvasható float.

**Visszatérési érték:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Visszaadja a keret magasságát. Csak olvasható float.

**Visszatérési érték:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Visszaadja a keret Z tengely körüli elforgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást jelzi. Csak olvasható float.

**Visszatérési érték:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Visszaadja a keret középpontjának X koordinátáját. Csak olvasható float.

**Visszatérési érték:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Visszaadja a keret középpontjának Y koordinátáját. Csak olvasható float.

**Visszatérési érték:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Megállapítja, hogy a keret vízszintesen tükrözött-e. Csak olvasható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Megállapítja, hogy a keret függőlegesen tükrözött-e. Csak olvasható [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Visszaadja a keret koordinátáit. Csak olvasható android.graphics.RectF.

**Visszatérési érték:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klónozza

**Visszatérési érték:**
java.lang.Object - Klónozott shape frame.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Klónozza.

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


Visszaad egy értéket, amely azt jelzi, hogy ez a példány egy megadott objektummal egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az objektum, amellyel az aktuális példányt összehasonlítjuk. |

**Visszatérési érték:**
boolean - **true** ha az obj egy ShapeFrame, amelynek értéke megegyezik ezzel a példánnyal; egyébként **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Visszaad egy értéket, amely azt jelzi, hogy ez a példány egy megadott objektummal egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | Az ShapeFRameEx, amelyet az aktuális példányhoz hasonlítunk. |

**Visszatérési érték:**
boolean - **true** ha a value egy ShapeFrame, amelynek értéke megegyezik ezzel a példánnyal; egyébként **false**.