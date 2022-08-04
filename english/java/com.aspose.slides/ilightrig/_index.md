---
title: ILightRig
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents LightRig.
type: docs
weight: 850
url: /java/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Represents LightRig.
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Light direction. Read/write [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Light direction. Read/write [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. Read/write [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. Read/write [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Latitude coordinate float |
| longitude | float | Longitude coordinate float |
| revolution | float | Revolution coordinate float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution.

**Returns:**
float[] - Rotation coordinates as float[]
