---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: 表示相机。
type: docs
url: /zh/com.aspose.slides/icamera/
---```
public interface ICamera
```

表示相机。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [setCameraType(int value)](#setCameraType-int-) | 相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相机视场角（0-180 度，视野） 读/写 float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相机视场角（0-180 度，视野） 读/写 float。 |
| [getZoom()](#getZoom--) | 相机缩放（以百分比表示的正值） 读/写 float。 |
| [setZoom(float value)](#setZoom-float-) | 相机缩放（以百分比表示的正值） 读/写 float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，作为纬度和经度坐标。 |
| [getRotation()](#getRotation--) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，作为纬度和经度坐标。 |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回值：**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相机视场角（0-180 度，视野） 读/写 float。

**返回值：**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

相机视场角（0-180 度，视野） 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相机缩放（以百分比表示的正值） 读/写 float。

**返回值：**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

相机缩放（以百分比表示的正值） 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，作为纬度和经度坐标。如果任意坐标值为 Float.NaN，则所有旋转未定义。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| latitude | float | 纬度值 float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，作为纬度和经度坐标。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。如果未定义旋转，则返回 null。

**返回值：**
float[] - Array of rotation values as float[].