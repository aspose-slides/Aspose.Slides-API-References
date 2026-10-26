---
title: IGlow
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt einen Glow-Effekt dar, bei dem ein farbiger unscharfer Umriss außerhalb der Objektkanten hinzugefügt wird.
type: docs
url: /de/com.aspose.slides/iglow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Stellt einen Glow-Effekt dar, bei dem ein unscharfer farbiger Umriss außerhalb der Objektkanten hinzugefügt wird.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Radius. |
| [setRadius(double value)](#setRadius-double-) | Radius. |
| [getColor()](#getColor--) | Farbformat. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Radius. Lese-/Schreib double.

**Rückgabe:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Radius. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Farbformat. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)