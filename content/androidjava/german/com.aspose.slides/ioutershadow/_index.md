---
title: IOuterShadow
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen äußeren Schatteneffekt dar.
type: docs
url: /de/com.aspose.slides/ioutershadow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Stellt einen äußeren Schatteneffekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Unschärferadius, in Punkten. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Unschärferadius, in Punkten. |
| [getDirection()](#getDirection--) | Richtung des Schattens, in Grad. |
| [setDirection(float value)](#setDirection-float-) | Richtung des Schattens, in Grad. |
| [getDistance()](#getDistance--) | Abstand des Schattens vom Objekt, in Punkten. |
| [setDistance(double value)](#setDistance-double-) | Abstand des Schattens vom Objekt, in Punkten. |
| [getShadowColor()](#getShadowColor--) | Farbe des Schattens. |
| [getRectangleAlign()](#getRectangleAlign--) | Rechteckausrichtung. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Rechteckausrichtung. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Horizontaler Schrägwinkel, in Grad. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Horizontaler Schrägwinkel, in Grad. |
| [getSkewVertical()](#getSkewVertical--) | Vertikaler Schrägwinkel, in Grad. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Vertikaler Schrägwinkel, in Grad. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Gibt an, ob der Schatten zusammen mit der Form rotiert. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Gibt an, ob der Schatten zusammen mit der Form rotiert. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Horizontaler Skalierungsfaktor, in Prozent der Originalgröße. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Horizontaler Skalierungsfaktor, in Prozent der Originalgröße. |
| [getScaleVertical()](#getScaleVertical--) | Vertikaler Skalierungsfaktor, in Prozent der Originalgröße. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Vertikaler Skalierungsfaktor, in Prozent der Originalgröße. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Unschärferadius, in Punkten. Standardwert - 0 pt. Lese/Schreib double.

**Rückgabe:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Unschärferadius, in Punkten. Standardwert - 0 pt. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Richtung des Schattens, in Grad. Standardwert - 0 � (von links nach rechts). Lese/Schreib float.

**Rückgabe:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Richtung des Schattens, in Grad. Standardwert - 0 � (von links nach rechts). Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Abstand des Schattens vom Objekt, in Punkten. Standardwert - 0 pt. Lese/Schreib double.

**Rückgabe:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Abstand des Schattens vom Objekt, in Punkten. Standardwert - 0 pt. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Farbe des Schattens. Standardwert - automatisches Schwarz (themenabhängig). Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

Rechteckausrichtung. Standardwert - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lese/Schreib [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Rückgabe:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

Rechteckausrichtung. Standardwert - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Lese/Schreib [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

Horizontaler Schrägwinkel, in Grad. Standardwert - 0 �. Lese/Schreib double.

**Rückgabe:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

Horizontaler Schrägwinkel, in Grad. Standardwert - 0 �. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

Vertikaler Schrägwinkel, in Grad. Standardwert - 0 �. Lese/Schreib double.

**Rückgabe:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

Vertikaler Schrägwinkel, in Grad. Standardwert - 0 �. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert - true. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

Gibt an, ob der Schatten zusammen mit der Form rotiert. Standardwert - true. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

Horizontaler Skalierungsfaktor, in Prozent der Originalgröße. Negatives Skalieren bewirkt eine Spiegelung. Standardwert - 100 %. Lese/Schreib double.

**Rückgabe:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

Horizontaler Skalierungsfaktor, in Prozent der Originalgröße. Negatives Skalieren bewirkt eine Spiegelung. Standardwert - 100 %. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

Vertikaler Skalierungsfaktor, in Prozent der Originalgröße. Negatives Skalieren bewirkt eine Spiegelung. Standardwert - 100 %. Lese/Schreib double.

**Rückgabe:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

Vertikaler Skalierungsfaktor, in Prozent der Originalgröße. Negatives Skalieren bewirkt eine Spiegelung. Standardwert - 100 %. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |