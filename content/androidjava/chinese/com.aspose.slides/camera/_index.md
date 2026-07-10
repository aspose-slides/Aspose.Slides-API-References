---
title: Camera
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Camera。
type: docs
url: /zh/com.aspose.slides/camera/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已实现的接口:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

表示 Camera。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Camera 类型。 |
| [setCameraType(int value)](#setCameraType-int-) | Camera 类型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 度，视场)。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 度，视场)。 |
| [getZoom()](#getZoom--) | Camera zoom (正值，以百分比表示)。 |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (正值，以百分比表示)。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 通过使用纬度坐标、经度坐标和围绕轴的旋转来定义旋转，以纬度和经度坐标为轴。 |
| [getRotation()](#getRotation--) | 通过使用纬度坐标、经度坐标和围绕轴的旋转来定义旋转，以纬度和经度坐标为轴。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回:**  
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Camera 类型。读写 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**返回:**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Camera 类型。读写 [CameraPresetType](../../com.aspose.slides/camerapresettype).

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Camera FOV (0-180 度，视场)。读写 float.

**返回:**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Camera FOV (0-180 度，视场)。读写 float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Camera zoom (正值，以百分比表示)。读写 float.

**返回:**  
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Camera zoom (正值，以百分比表示)。读写 float.

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

通过使用纬度坐标、经度坐标和围绕轴的旋转来定义旋转，以纬度和经度坐标为轴。如果任一坐标值为 Float.NaN，则所有旋转未定义。

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

通过使用纬度坐标、经度坐标和围绕轴的旋转来定义旋转，以纬度和经度坐标为轴。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。如果未定义旋转，则返回 null。

**返回:**  
float[]