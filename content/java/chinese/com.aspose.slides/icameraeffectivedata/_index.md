---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /zh/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

不可变对象，包含有效的相机属性。

--------------------

此接口用作 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相机类型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相机视场（0-180 deg, field of View）。 |
| [getZoom()](#getZoom--) | 相机缩放（正值，以百分比表示）。 |
| [getRotation()](#getRotation--) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相机类型。只读 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相机视场（0-180 deg, field of View）。只读 float。

**返回:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相机缩放（正值，以百分比表示）。只读 float。

**返回:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的。返回数组的第一个元素为纬度，第二个元素为经度，第三个元素为旋转。如果未定义旋转，则返回 null。

**返回:**
float[] - 以 float[] 形式的旋转值数组。