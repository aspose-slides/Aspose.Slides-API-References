---
title: IOuterShadow
second_title: Aspose.Slides Java API-referencia
description: Képviseli a külső árnyék effektust.
type: docs
url: /hu/com.aspose.slides/ioutershadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Képviseli a külső árnyék effektust.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur sugár, pontban. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur sugár, pontban. |
| [getDirection()](#getDirection--) | Az árnyék iránya fokban. |
| [setDirection(float value)](#setDirection-float-) | Az árnyék iránya fokban. |
| [getDistance()](#getDistance--) | Az árnyék távolsága az objektumtól, pontban. |
| [setDistance(double value)](#setDistance-double-) | Az árnyék távolsága az objektumtól, pontban. |
| [getShadowColor()](#getShadowColor--) | Az árnyék színe. |
| [getRectangleAlign()](#getRectangleAlign--) | Téglalap igazítás. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Téglalap igazítás. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Vízszintes ferdeségi szög fokban. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Vízszintes ferdeségi szög fokban. |
| [getSkewVertical()](#getSkewVertical--) | Függőleges ferdeségi szög fokban. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Függőleges ferdeségi szög fokban. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Jelzi, hogy az árnyék együtt forog-e az alakzattal. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Jelzi, hogy az árnyék együtt forog-e az alakzattal. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Vízszintes méretezési tényező, az eredeti méret százalékában. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Vízszintes méretezési tényező, az eredeti méret százalékában. |
| [getScaleVertical()](#getScaleVertical--) | Függőleges méretezési tényező, az eredeti méret százalékában. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Függőleges méretezési tényező, az eredeti méret százalékában. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Blur sugár, pontban. Alapértelmezett érték - 0 pt. Olvasás/írás double.

**Visszatérési érték:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Blur sugár, pontban. Alapértelmezett érték - 0 pt. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Az árnyék iránya fokban. Alapértelmezett érték - 0 � (balról jobbra). Olvasás/írás float.

**Visszatérési érték:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Az árnyék iránya fokban. Alapértelmezett érték - 0 � (balról jobbra). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Az árnyék távolsága az objektumtól, pontban. Alapértelmezett érték - 0 pt. Olvasás/írás double.

**Visszatérési érték:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Az árnyék távolsága az objektumtól, pontban. Alapértelmezett érték - 0 pt. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Az árnyék színe. Alapértelmezett érték - automatikus fekete (témafüggő). Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Téglalap igazítás. Alapértelmezett érték - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Olvasás/írás [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Visszatérési érték:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Téglalap igazítás. Alapértelmezett érték - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Olvasás/írás [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Vízszintes ferdeségi szög fokban. Alapértelmezett érték - 0 �. Olvasás/írás double.

**Visszatérési érték:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Vízszintes ferdeségi szög fokban. Alapértelmezett érték - 0 �. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Függőleges ferdeségi szög fokban. Alapértelmezett érték - 0 �. Olvasás/írás double.

**Visszatérési érték:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Függőleges ferdeségi szög fokban. Alapértelmezett érték - 0 �. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Jelzi, hogy az árnyék együtt forog-e az alakzattal. Alapértelmezett érték - true. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Jelzi, hogy az árnyék együtt forog-e az alakzattal. Alapértelmezett érték - true. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Vízszintes méretezési tényező, az eredeti méret százalékában. A negatív méretezés tükrözést okoz. Alapértelmezett érték - 100 %. Olvasás/írás double.

**Visszatérési érték:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Vízszintes méretezési tényező, az eredeti méret százalékában. A negatív méretezés tükrözést okoz. Alapértelmezett érték - 100 %. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Függőleges méretezési tényező, az eredeti méret százalékában. A negatív méretezés tükrözést okoz. Alapértelmezett érték - 100 %. Olvasás/írás double.

**Visszatérési érték:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Függőleges méretezési tényező, az eredeti méret százalékában. A negatív méretezés tükrözést okoz. Alapértelmezett érték - 100 %. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |