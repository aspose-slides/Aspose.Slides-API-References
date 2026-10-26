---
title: IInnerShadow
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen inneren Schatteneffekt dar.
type: docs
url: /de/com.aspose.slides/iinnershadow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

Stellt einen inneren Schatteneffekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Unschärferadius. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Unschärferadius. |
| [getDirection()](#getDirection--) | Richtung des Schattens. |
| [setDirection(float value)](#setDirection-float-) | Richtung des Schattens. |
| [getDistance()](#getDistance--) | Abstand des Schattens. |
| [setDistance(double value)](#setDistance-double-) | Abstand des Schattens. |
| [getShadowColor()](#getShadowColor--) | Farbe des Schattens. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Unschärferadius. Lesen/Schreiben double.

**Rückgabewert:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Unschärferadius. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Richtung des Schattens. Lesen/Schreiben float.

**Rückgabewert:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Richtung des Schattens. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Abstand des Schattens. Lesen/Schreiben double.

**Rückgabewert:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Abstand des Schattens. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Farbe des Schattens. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)