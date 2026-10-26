---
title: Camera
second_title: Aspose.Slides for Java API 参考
description: 表示相机。
type: docs
url: /zh/com.aspose.slides/camera/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

表示相机。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | 相机类型。 |
| [setCameraType(int value)](#setCameraType-int-) | 相机类型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相机视野（0-180 度，视场）。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相机视野（0-180 度，视场）。 |
| [getZoom()](#getZoom--) | 相机缩放（百分比的正值）。 |
| [setZoom(float value)](#setZoom-float-) | 相机缩放（百分比的正值）。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标作为参考。 |
| [getRotation()](#getRotation--) | 旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标作为参考。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**  
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

相机类型。读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回：**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

相机类型。读/写 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

相机视野（0-180 度，视场）。读/写 float。

**返回：**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

相机视野（0-180 度，视场）。读/写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

相机缩放（百分比的正值）。读/写 float。

**返回：**  
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

相机缩放（百分比的正值）。读/写 float。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标作为参考。如果任意坐标值为 Float.NaN，则所有旋转均未定义。

**参数：**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

旋转是通过使用纬度坐标、经度坐标以及围绕轴的旋转来定义的，纬度和经度坐标作为参考。返回数组的第一个元素为纬度，第二个为经度，第三个为旋转。如果未定义旋转，则返回 null。

**返回：**  
float[]