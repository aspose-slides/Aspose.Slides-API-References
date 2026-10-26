---
title: IGlow
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een gloeieffect voor waarin een onscherpe gekleurde omtrek buiten de randen van het object wordt toegevoegd.
type: docs
url: /nl/com.aspose.slides/iglow/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Stelt een gloeieffect voor, waarin een onscherpe gekleurde omtrek buiten de randen van het object wordt toegevoegd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Kleurformaat. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radius. Lezen/Schrijven double.

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radius. Lezen/Schrijven double.

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