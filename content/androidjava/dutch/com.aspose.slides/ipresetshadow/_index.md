---
title: IPresetShadow
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een vooraf ingesteld schaduweffect voor.
type: docs
url: /nl/com.aspose.slides/ipresetshadow/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Stelt een vooraf ingestelde schaduweffect voor.
## Methoden

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Richting van schaduw. |
| [setDirection(float value)](#setDirection-float-) | Richting van schaduw. |
| [getDistance()](#getDistance--) | Afstand van schaduw. |
| [setDistance(double value)](#setDistance-double-) | Afstand van schaduw. |
| [getShadowColor()](#getShadowColor--) | Kleur van schaduw. |
| [getPreset()](#getPreset--) | Voorinstelling. |
| [setPreset(int value)](#setPreset-int-) | Voorinstelling. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Richting van schaduw. Lezen/Schrijven float.

**Retourwaarde:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Richting van schaduw. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Afstand van schaduw. Lezen/Schrijven double.

**Retourwaarde:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Afstand van schaduw. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Kleur van schaduw. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourwaarde:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Voorinstelling. Lezen/Schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Retourwaarde:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```

Voorinstelling. Lezen/Schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |