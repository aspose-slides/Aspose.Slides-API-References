---
title: LightRig
second_title: Aspose.Slides Java API 레퍼런스
description: LightRig을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/lightrig/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Light direction. |
| [setDirection(int value)](#setDirection-int-) | Light direction. |
| [getLightType()](#getLightType--) | Represents a preset light right that can be applied to a shape. |
| [setLightType(int value)](#setLightType-int-) | Represents a preset light right that can be applied to a shape. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**  
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

조명 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**반환:**  
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

조명 방향. 읽기/쓰기 [LightingDirection](../../com.aspose.slides/lightingdirection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**반환:**  
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

Represents a preset light right that can be applied to a shape. The light rig represents a group of lights oriented in a specific way relative to a 3D scene. 읽기/쓰기 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is Float.NaN, all rotation is undefined.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined.

**반환:**  
float[]