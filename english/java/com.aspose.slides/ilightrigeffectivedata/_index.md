---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description:  Immutable object which contains effective light rig properties.
type: docs
weight: 851
url: /java/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Immutable object which contains effective light rig properties.

--------------------

This interface is used as a part of [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Light direction. Read-only [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. Read-only [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. First element in return array - latitude, second - longitude, third - revolution.

**Returns:**
float[] - Rotation coordinates as float[]
