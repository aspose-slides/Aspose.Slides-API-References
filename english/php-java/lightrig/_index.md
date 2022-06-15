---
title: LightRig
type: docs
weight: 0
url: /php-java/lightrig/
---

# LightRig class

 Represents LightRig.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getDirection](/slides/php-java/lightrig/getdirection/)() | int | Light direction. Read/write LightingDirection. |
| [getLightType](/slides/php-java/lightrig/getlighttype/)() | int | Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. Read/write LightRigPresetType. |
| [getRotation](/slides/php-java/lightrig/getrotation/)() | float | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined. |
| [setDirection](/slides/php-java/lightrig/setdirection/)(int) | void | Light direction. Read/write LightingDirection. |
| [setLightType](/slides/php-java/lightrig/setlighttype/)(int) | void | Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. Read/write LightRigPresetType. |
| [setRotation](/slides/php-java/lightrig/setrotation/)(float, float, float) | void | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is Float.NaN, all rotation is undefined. |
