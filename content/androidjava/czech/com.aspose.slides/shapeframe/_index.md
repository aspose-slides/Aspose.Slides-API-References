---
title: ShapeFrame
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje vlastnosti rámců tvarů.
type: docs
url: /cs/com.aspose.slides/shapeframe/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

Reprezentuje vlastnosti rámce tvaru.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | Vytvoří nové vlastnosti rámce tvaru. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getX()](#getX--) | Vrací souřadnici X levého horního rohu rámce. |
| [getY()](#getY--) | Vrací souřadnici Y levého horního rohu rámce. |
| [getWidth()](#getWidth--) | Vrací šířku rámce. |
| [getHeight()](#getHeight--) | Vrací výšku rámce. |
| [getRotation()](#getRotation--) | Vrací počet stupňů, o které je rámec otočen kolem osy z. |
| [getCenterX()](#getCenterX--) | Vrací souřadnici X středu rámce. |
| [getCenterY()](#getCenterY--) | Vrací souřadnici Y středu rámce. |
| [getFlipH()](#getFlipH--) | Určuje, zda je rámec horizontálně převrácen. |
| [getFlipV()](#getFlipV--) | Určuje, zda je rámec vertikálně převrácen. |
| [getRectangle()](#getRectangle--) | Vrací souřadnice rámce. |
| [deepClone()](#deepClone--) | Klonuje |
| [cloneT()](#cloneT--) | Klonuje. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Vrací hodnotu určující, zda je tato instance rovna zadanému objektu. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | Vrací hodnotu určující, zda je tato instance rovna zadanému objektu. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```


Vytvoří nové vlastnosti rámce tvaru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | Souřadnice X rámce. |
| y | float | Souřadnice Y rámce. |
| width | float | Šířka rámce. |
| height | float | Výška rámce. |
| flipH | byte | True, pokud je rámec horizontálně převrácen. |
| flipV | byte | True, pokud je rámec vertikálně převrácen. |
| rotationAngle | float | Počet stupňů, o které je rámec otočen. |

### getX() {#getX--}
```
public final float getX()
```


Vrací souřadnici X levého horního rohu rámce. Pouze pro čtení float.

**Vrací:**
float
### getY() {#getY--}
```
public final float getY()
```


Vrací souřadnici Y levého horního rohu rámce. Pouze pro čtení float.

**Vrací:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Vrací šířku rámce. Pouze pro čtení float.

**Vrací:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Vrací výšku rámce. Pouze pro čtení float.

**Vrací:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```


Vrací počet stupňů, o které je rámec otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí proti směru hodinových ručiček. Pouze pro čtení float.

**Vrací:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Vrací souřadnici X středu rámce. Pouze pro čtení float.

**Vrací:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Vrací souřadnici Y středu rámce. Pouze pro čtení float.

**Vrací:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```


Určuje, zda je rámec horizontálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```


Určuje, zda je rámec vertikálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getRectangle() {#getRectangle--}
```
public final RectF getRectangle()
```


Vrací souřadnice rámce. Pouze pro čtení android.graphics.RectF.

**Vrací:**
android.graphics.RectF
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klonuje

**Vrací:**
java.lang.Object - Klonovaný rámec tvaru.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```


Klonuje.

**Vrací:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - Klonovaný rámec tvaru.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Vrací:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vrací hodnotu určující, zda je tato instance rovna zadanému objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt, se kterým se má instance porovnat. |

**Vrací:**
boolean - **true** pokud je obj ShapeFrame, který má stejnou hodnotu jako tato instance; jinak **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```


Vrací hodnotu určující, zda je tato instance rovna zadanému objektu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx, se kterým se má instance porovnat. |

**Vrací:**
boolean - **true** pokud je value ShapeFrame, který má stejnou hodnotu jako tato instance; jinak **false**.