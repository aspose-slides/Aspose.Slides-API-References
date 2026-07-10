---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 LightRig。
type: docs
url: /zh/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

表示 LightRig。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 光方向。 |
| [setDirection(int value)](#setDirection-int-) | 光方向。 |
| [getLightType()](#getLightType--) | 表示可应用于形状的预设右侧光。 |
| [setLightType(int value)](#setLightType-int-) | 表示可应用于形状的预设右侧光。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。 |
| [getRotation()](#getRotation--) | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光方向。读/写 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**返回值:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

光方向。读/写 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

表示可应用于形状的预设右侧光。光线装置表示相对于 3D 场景以特定方式定向的一组光源。读/写 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**返回值:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

表示可应用于形状的预设右侧光。光线装置表示相对于 3D 场景以特定方式定向的一组光源。读/写 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| latitude | float | 纬度坐标 float |
| longitude | float | 经度坐标 float |
| revolution | float | 旋转坐标 float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。

**返回值:**
float[] - 旋转坐标的 float[]