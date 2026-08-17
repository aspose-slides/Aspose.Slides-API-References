---
title: IOuterShadow
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Outer Shadow-Effekt dar.
type: docs
url: /de/com.aspose.slides/ioutershadow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Stellt einen Outer Shadow-Effekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Blur radius, in points. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Blur radius, in points. |
| [getDirection()](#getDirection--) | Direction of the shadow, in degrees. |
| [setDirection(float value)](#setDirection-float-) | Direction of the shadow, in degrees. |
| [getDistance()](#getDistance--) | Distance of the shadow from the object, in points. |
| [setDistance(double value)](#setDistance-double-) | Distance of the shadow from the object, in points. |
| [getShadowColor()](#getShadowColor--) | Color of the shadow. |
| [getRectangleAlign()](#getRectangleAlign--) | Rectangle alignment. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rectangle alignment. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Horizontal skew angle, in degrees. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Horizontal skew angle, in degrees. |
| [getSkewVertical()](#getSkewVertical--) | Vertical skew angle, in degrees. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Vertical skew angle, in degrees. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Indicates whether the shadow rotates together with the shape. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Indicates whether the shadow rotates together with the shape. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Horizontal scaling factor, in percent of the original size. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Horizontal scaling factor, in percent of the original size. |
| [getScaleVertical()](#getScaleVertical--) | Vertical scaling factor, in percent of the original size. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Vertical scaling factor, in percent of the original size. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Blur-Radius in Punkten. Standardwert – 0 pt. Lese-/Schreib double.

**Rückgabewert:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Blur-Radius in Punkten. Standardwert – 0 pt. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Richtung des Schattens in Grad. Standardwert – 0 � (left-to-right). Lese-/Schreib float.

**Rückgabewert:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Richtung des Schattens in Grad. Standardwert – 0 � (left-to-right). Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Abstand des Schattens vom Objekt in Punkten. Standardwert – 0 pt. Lese-/Schreib double.

**Rückgabewert:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Abstand des Schattens vom Objekt in Punkten. Standardwert – 0 pt. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Farbe des Schattens. Standardwert – automatisches Schwarz (themenabhängig). Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Rechteckausrichtung. Standardwert – [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lese-/Schreib [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Rückgabewert:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Rechteckausrichtung. Standardwert – [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lese-/Schreib [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Horizontaler Schrägwinkel in Grad. Standardwert – 0 �. Lese-/Schreib double.

**Rückgabewert:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Horizontaler Schrägwinkel in Grad. Standardwert – 0 �. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Vertikaler Schrägwinkel in Grad. Standardwert – 0 �. Lese-/Schreib double.

**Rückgabewert:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Vertikaler Schrägwinkel in Grad. Standardwert – 0 �. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert – true. Lese-/Schreib boolean.

**Rückgabewert:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert – true. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Horizontaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lese-/Schreib double.

**Rückgabewert:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Horizontaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Vertikaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lese-/Schreib double.

**Rückgabewert:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Vertikaler Skalierungsfaktor in Prozent der Originalgröße. Negative Skalierung bewirkt eine Spiegelung. Standardwert – 100 %. Lese-/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |