---
title: PresetShadow
second_title: Aspose.Slides for Java API Reference
description: Represents a Preset Shadow effect.
type: docs
weight: 454
url: /com.aspose.slides/presetshadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
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
| [getEffective()](#getEffective--) | Gets effective Preset Shadow effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [PresetShadow](../../com.aspose.slides/presetshadow) is equal to the current [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


Direction of shadow. Read/write  float .

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


Direction of shadow. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```


Distance of shadow. Read/write  double .

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


Distance of shadow. Read/write  double .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


Color of shadow. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```


Preset. Read/write [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Returns:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```


Preset. Read/write [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```


Gets effective Preset Shadow effect data with the inheritance applied.

**Returns:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returns parent IPresentationComponent. Read-only [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [PresetShadow](../../com.aspose.slides/presetshadow) is equal to the current [PresetShadow](../../com.aspose.slides/presetshadow).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [PresetShadow](../../com.aspose.slides/presetshadow) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
