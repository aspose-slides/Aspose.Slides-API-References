---
title: IShapeFrame
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje vlastnosti rámců tvaru.
type: docs
url: /cs/com.aspose.slides/ishapeframe/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Představuje vlastnosti rámce tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getX()](#getX--) | Vrací souřadnici X levého horního rohu rámce. |
| [getY()](#getY--) | Vrací souřadnici Y levého horního rohu rámce. |
| [getWidth()](#getWidth--) | Vrací šířku rámce. |
| [getHeight()](#getHeight--) | Vrací výšku rámce. |
| [getRotation()](#getRotation--) | Vrací počet stupňů, o který je rámec otočen kolem osy z. |
| [getCenterX()](#getCenterX--) | Vrací souřadnici X středu rámce. |
| [getCenterY()](#getCenterY--) | Vrací souřadnici Y středu rámce. |
| [getFlipH()](#getFlipH--) | Určuje, zda je rámec horizontálně převrácen. |
| [getFlipV()](#getFlipV--) | Určuje, zda je rámec vertikálně převrácen. |
| [getRectangle()](#getRectangle--) | Vrací souřadnice rámce. |
### getX() {#getX--}
```
public abstract float getX()
```


Vrací souřadnici X levého horního rohu rámce. Pouze pro čtení float.

**Vrací:**
float
### getY() {#getY--}
```
public abstract float getY()
```


Vrací souřadnici Y levého horního rohu rámce. Pouze pro čtení float.

**Vrací:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Vrací šířku rámce. Pouze pro čtení float.

**Vrací:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Vrací výšku rámce. Pouze pro čtení float.

**Vrací:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Vrací počet stupňů, o který je rámec otočen kolem osy z. Pozitivní hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Pouze pro čtení float.

**Vrací:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


Vrací souřadnici X středu rámce. Pouze pro čtení float.

**Vrací:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


Vrací souřadnici Y středu rámce. Pouze pro čtení float.

**Vrací:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


Určuje, zda je rámec horizontálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


Určuje, zda je rámec vertikálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


Vrací souřadnice rámce. Pouze pro čtení java.awt.geom.Rectangle2D.Float.

**Vrací:**
java.awt.geom.Rectangle2D.Float