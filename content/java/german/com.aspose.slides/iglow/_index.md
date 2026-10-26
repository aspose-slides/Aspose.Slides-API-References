---
title: IGlow
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Glow-Effekt dar, bei dem ein farbiger, unscharfer Umriss außerhalb der Kanten des Objekts hinzugefügt wird.
type: docs
url: /de/com.aspose.slides/iglow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Stellt einen Glow-Effekt dar, bei dem ein farbiger, unscharfer Umriss außerhalb der Kanten des Objekts hinzugefügt wird.
## Methoden

| Method | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Color format. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radius. Lesen/Schreiben double.

**Rückgabe:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radius. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Color format. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)