---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /zh/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

不可变对象，包含有效灯光装置属性。

--------------------

此接口用作 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 光方向。 |
| [getLightType()](#getLightType--) | 表示可以应用于形状的预设光方向。 |
| [getRotation()](#getRotation--) | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

光方向。只读 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**返回：**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

表示可以应用于形状的预设光方向。灯光装置表示相对于 3D 场景以特定方式定向的一组灯光。只读 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**返回：**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。

**返回：**
float[] - 旋转坐标为 float[]