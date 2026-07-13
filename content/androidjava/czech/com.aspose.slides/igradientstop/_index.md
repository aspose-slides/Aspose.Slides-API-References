---
title: IGradientStop
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje formát gradientu.
type: docs
url: /cs/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Reprezentuje formát gradientu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPosition()](#getPosition--) | Returns or sets the position (0..1) of a gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Returns or sets the position (0..1) of a gradient stop. |
| [getColor()](#getColor--) | Returns the color of a gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Vrací nebo nastavuje pozici (0..1) gradientového zastavení. Čtení/zápis float.

**Vrací:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Vrací nebo nastavuje pozici (0..1) gradientového zastavení. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Vrací barvu gradientového zastavení. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)