---
title: IGlow
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een gloeieffect waarbij een kleurvervaging rond de randen van het object wordt toegevoegd.
type: docs
url: /nl/com.aspose.slides/iglow/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Stelt een gloeieffect voor, waarbij een kleurvervaging rondom de randen van het object wordt toegevoegd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Straal. |
| [setRadius(double value)](#setRadius-double-) | Straal. |
| [getColor()](#getColor--) | Kleurformaat. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Straal. Lezen/schrijven double.

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Straal. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Kleurformaat. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)