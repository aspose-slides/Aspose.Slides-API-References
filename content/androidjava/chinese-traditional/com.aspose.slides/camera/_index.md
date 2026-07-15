---
title: Camera
second_title: Aspose.Slides for Android 之 Java API 參考
description: 代表 Camera。
type: docs
url: /zh-hant/com.aspose.slides/camera/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面：**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

代表 Camera。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | 相機類型。 |
| [setCameraType(int value)](#setCameraType-int-) | 相機類型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機視野 (0-180 度, field of View)。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相機視野 (0-180 度, field of View)。 |
| [getZoom()](#getZoom--) | 相機縮放 (正值，以百分比表示)。 |
| [setZoom(float value)](#setZoom-float-) | 相機縮放 (正值，以百分比表示)。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及圍繞軸線的旋轉來定義的，緯度和經度座標即為此旋轉的座標。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及圍繞軸線的旋轉來定義的，緯度和經度座標即為此旋轉的座標。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只讀 long.

**Returns:**
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

相機類型。可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**Returns:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

相機類型。可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

相機視野 (0-180 度, field of View)。可讀寫 float。

**Returns:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

相機視野 (0-180 度, field of View)。可讀寫 float。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

相機縮放 (正值，以百分比表示)。可讀寫 float。

**Returns:**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

相機縮放 (正值，以百分比表示)。可讀寫 float。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標，以及圍繞軸線的旋轉來定義的，緯度和經度座標即為此旋轉的座標。如果任何座標值為 Float.NaN，則所有旋轉皆未定義。

**Parameters:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及圍繞軸線的旋轉來定義的，緯度和經度座標即為此旋轉的座標。返回陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。如果未定義旋轉，則返回 null。

**Returns:**
float[]