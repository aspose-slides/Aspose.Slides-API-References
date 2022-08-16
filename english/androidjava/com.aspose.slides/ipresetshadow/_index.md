---
title: IPresetShadow
second_title: Aspose.Slides for Android via Java API Reference
description:  Represents a Preset Shadow effect.
type: docs
weight: 982
url: /androidjava/com.aspose.slides/ipresetshadow/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Represents a Preset Shadow effect.
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of shadow. |
| [setDirection(float value)](#setDirection-float-) | Direction of shadow. |
| [getDistance()](#getDistance--) | Distance of shadow. |
| [setDistance(double value)](#setDistance-double-) | Distance of shadow. |
| [getShadowColor()](#getShadowColor--) | Color of shadow. |
| [getPreset()](#getPreset--) | Preset. |
| [setPreset(int value)](#setPreset-int-) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Direction of shadow. Read/write float.

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Direction of shadow. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Distance of shadow. Read/write double.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Distance of shadow. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Color of shadow. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Preset. Read/write [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returns:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Preset. Read/write [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

