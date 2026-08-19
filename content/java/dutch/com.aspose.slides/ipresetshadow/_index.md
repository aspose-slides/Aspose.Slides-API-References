---
title: IPresetShadow
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een vooraf ingestelde schaduweffect voor.
type: docs
url: /nl/com.aspose.slides/ippresetshadow/
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


Richting van schaduw. Lezen/schrijven float.

**Retour:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Richting van schaduw. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Afstand van schaduw. Lezen/schrijven double.

**Retour:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Afstand van schaduw. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Kleur van schaduw. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Voorinstelling. Lezen/schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Retour:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Voorinstelling. Lezen/schrijven [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |