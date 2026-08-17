---
title: ICamera
second_title: Aspose.Slides for Java API Reference
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
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相机视野 (0-180 度, field of View) 读/写 float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相机视野 (0-180 度, field of View) 读/写 float。 |
| [getZoom()](#getZoom--) | 相机缩放 (正值，以百分比表示) 读/写 float。 |
| [setZoom(float value)](#setZoom-float-) | 相机缩放 (正值，以百分比表示) 读/写 float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴线的旋转来定义的，纬度和经度坐标作为旋转轴。 |
| [getRotation()](#getRotation--) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴线的旋转来定义的，纬度和经度坐标作为旋转轴。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

相机类型 读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相机视野 (0-180 度, field of View) 读/写 float。

**返回:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

相机视野 (0-180 度, field of View) 读/写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相机缩放 (正值，以百分比表示) 读/写 float。

**返回:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

相机缩放 (正值，以百分比表示) 读/写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴线的旋转来定义的。如果任一坐标值为 Float.NaN，则所有旋转均未定义。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| latitude | float | 纬度值 float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴线的旋转来定义的。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。如果未定义旋转，则返回 null。

**返回:**
float[] - 以 float[] 形式的旋转值数组。