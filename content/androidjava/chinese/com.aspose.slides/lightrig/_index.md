---
title: LightRig
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 LightRig。
type: docs
url: /zh/com.aspose.slides/lightrig/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已实现的接口:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

表示 LightRig。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | 灯光方向。 |
| [setDirection(int value)](#setDirection-int-) | 灯光方向。 |
| [getLightType()](#getLightType--) | 表示可以应用于形状的预设右侧灯光。 |
| [setLightType(int value)](#setLightType-int-) | 表示可以应用于形状的预设右侧灯光。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标即为这些坐标。 |
| [getRotation()](#getRotation--) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标即为这些坐标。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

灯光方向。可读写 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**返回：**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

灯光方向。可读写 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

表示可以应用于形状的预设右侧灯光。光照装置表示相对于 3D 场景以特定方式定位的一组灯光。可读写 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**返回：**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

表示可以应用于形状的预设右侧灯光。光照装置表示相对于 3D 场景以特定方式定位的一组灯光。可读写 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标即为这些坐标。如果任意坐标值为 Float.NaN，则所有旋转均未定义。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标即为这些坐标。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。如果未定义旋转，则返回 null。

**返回：**
float[]