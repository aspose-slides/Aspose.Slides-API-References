---
title: IShapeFrame
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje vlastnosti rámců tvarů.
type: docs
url: /cs/com.aspose.slides/ishapeframe/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

Reprezentuje vlastnosti rámce tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getX()](#getX--) | Vrací souřadnici X levého horního rohu rámečku. |
| [getY()](#getY--) | Vrací souřadnici Y levého horního rohu rámečku. |
| [getWidth()](#getWidth--) | Vrací šířku rámečku. |
| [getHeight()](#getHeight--) | Vrací výšku rámečku. |
| [getRotation()](#getRotation--) | Vrací počet stupňů, o které je rámeček otočen kolem osy z. |
| [getCenterX()](#getCenterX--) | Vrací souřadnici X středu rámečku. |
| [getCenterY()](#getCenterY--) | Vrací souřadnici Y středu rámečku. |
| [getFlipH()](#getFlipH--) | Určuje, zda je rámeček horizontálně převrácen. |
| [getFlipV()](#getFlipV--) | Určuje, zda je rámeček vertikálně převrácen. |
| [getRectangle()](#getRectangle--) | Vrací souřadnice rámečku. |
### getX() {#getX--}
```
public abstract float getX()
```

Vrací souřadnici X levého horního rohu rámečku. Pouze pro čtení float.

**Vrací:**
float
### getY() {#getY--}
```
public abstract float getY()
```

Vrací souřadnici Y levého horního rohu rámečku. Pouze pro čtení float.

**Vrací:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Vrací šířku rámečku. Pouze pro čtení float.

**Vrací:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Vrací výšku rámečku. Pouze pro čtení float.

**Vrací:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Vrací počet stupňů, o které je rámeček otočen kolem osy z. Kladná hodnota označuje otočení po směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Pouze pro čtení float.

**Vrací:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```

Vrací souřadnici X středu rámečku. Pouze pro čtení float.

**Vrací:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```

Vrací souřadnici Y středu rámečku. Pouze pro čtení float.

**Vrací:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```

Určuje, zda je rámeček horizontálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```

Určuje, zda je rámeček vertikálně převrácen. Pouze pro čtení [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```

Vrací souřadnice rámečku. Pouze pro čtení android.graphics.RectF.

**Vrací:**
android.graphics.RectF