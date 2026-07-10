---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 包含有效相机属性的不可变对象。
type: docs
url: /zh/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

包含有效相机属性的不可变对象。

--------------------

此接口作为 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分使用。

## 方法

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相机类型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相机视场角 (0-180 度，视野)。 |
| [getZoom()](#getZoom--) | 相机缩放（正值，以百分比表示）。 |
| [getRotation()](#getRotation--) | 通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转，纬度和经度坐标作为旋转轴。 |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相机类型。只读 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回：**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相机视场角（0-180 度，视野）。只读 float。

**返回：**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相机缩放（正值，以百分比表示）。只读 float。

**返回：**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义旋转，纬度和经度坐标作为旋转轴。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。若未定义旋转，则返回 null。

**返回：**
float[] - 旋转值数组，类型为 float[].