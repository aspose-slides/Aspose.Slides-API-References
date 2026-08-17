---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 不可变对象，包含有效的灯光装置属性。
type: docs
url: /zh/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

不可变对象，包含有效的灯光装置属性。

--------------------

此接口用作 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | 灯光方向。 |
| [getLightType()](#getLightType--) | 表示可应用于形状的预设灯光。 |
| [getRotation()](#getRotation--) | 旋转通过使用纬度坐标、经度坐标以及围绕轴的旋转（基于纬度和经度坐标）来定义。 |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


灯光方向。只读 [LightingDirection](../../com.aspose.slides/lightingdirection)。

**返回:**  
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


表示可应用于形状的预设灯光。光照装置表示相对于 3D 场景特定方式定位的一组灯光。只读 [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)。

**返回:**  
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


旋转通过使用纬度坐标、经度坐标以及围绕轴的旋转（基于纬度和经度坐标）来定义。返回数组的第一个元素 - 纬度，第二个元素 - 经度，第三个元素 - 旋转。

**返回:**  
float[] - 旋转坐标（float[]）