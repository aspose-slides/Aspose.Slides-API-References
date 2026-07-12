---
title: IPresetShadow
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen voreingestellten Schatteneffekt dar.
type: docs
url: /de/com.aspose.slides/ipresetshadow/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Stellt einen voreingestellten Schatteneffekt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDirection()](#getDirection--) | Richtung des Schattens. |
| [setDirection(float value)](#setDirection-float-) | Richtung des Schattens. |
| [getDistance()](#getDistance--) | Abstand des Schattens. |
| [setDistance(double value)](#setDistance-double-) | Abstand des Schattens. |
| [getShadowColor()](#getShadowColor--) | Farbe des Schattens. |
| [getPreset()](#getPreset--) | Voreinstellung. |
| [setPreset(int value)](#setPreset-int-) | Voreinstellung. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Richtung des Schattens. Lesen/Schreiben Float.

**Rückgabe:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Richtung des Schattens. Lesen/Schreiben Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Abstand des Schattens. Lesen/Schreiben Double.

**Rückgabe:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Abstand des Schattens. Lesen/Schreiben Double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Farbe des Schattens. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Voreinstellung. Lesen/Schreiben [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Rückgabe:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Voreinstellung. Lesen/Schreiben [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |