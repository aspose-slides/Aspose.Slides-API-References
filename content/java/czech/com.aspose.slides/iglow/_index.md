---
title: IGlow
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje efekt záře, ve kterém je kolem okrajů objektu přidán rozmazaný obrys v barvě.
type: docs
url: /cs/com.aspose.slides/iglow/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Reprezentuje efekt záře, ve kterém je kolem okrajů objektu přidán rozmazaný obrys v barvě.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Poloměr. |
| [setRadius(double value)](#setRadius-double-) | Poloměr. |
| [getColor()](#getColor--) | Formát barvy. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Poloměr. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Poloměr. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Formát barvy. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)