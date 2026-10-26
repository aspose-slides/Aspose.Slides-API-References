---
title: IPresetShadow
second_title: Aspose.Slides pro Java API Reference
description: Představuje efekt přednastaveného stínu.
type: docs
url: /cs/com.aspose.slides/ipresetshadow/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Představuje efekt přednastaveného stínu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDirection()](#getDirection--) | Směr stínu. |
| [setDirection(float value)](#setDirection-float-) | Směr stínu. |
| [getDistance()](#getDistance--) | Vzdálenost stínu. |
| [setDistance(double value)](#setDistance-double-) | Vzdálenost stínu. |
| [getShadowColor()](#getShadowColor--) | Barva stínu. |
| [getPreset()](#getPreset--) | Předvolba. |
| [setPreset(int value)](#setPreset-int-) | Předvolba. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Směr stínu. Čtení/Zápis float.

**Vrací:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Směr stínu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Vzdálenost stínu. Čtení/Zápis double.

**Vrací:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Vzdálenost stínu. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Barva stínu. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Předvolba. Čtení/Zápis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Vrací:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Předvolba. Čtení/Zápis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |