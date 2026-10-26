---
title: Camera
second_title: Aspose.Slides for Java API 參考
description: 表示相機。
type: docs
url: /zh-hant/com.aspose.slides/camera/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作介面:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

表示相機。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | 相機類型。 |
| [setCameraType(int value)](#setCameraType-int-) | 相機類型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機 FOV (0-180 度，視野)。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相機 FOV (0-180 度，視野)。 |
| [getZoom()](#getZoom--) | 相機縮放（以百分比表示的正值）。 |
| [setZoom(float value)](#setZoom-float-) | 相機縮放（以百分比表示的正值）。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及圍繞該軸的旋轉來定義的，緯度與經度座標用於此。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及圍繞該軸的旋轉來定義的，緯度與經度座標用於此。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。 唯讀 long.

**回傳:**  
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

相機類型。 讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**回傳:**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

相機類型。 讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

相機 FOV (0-180 度，視野)。 讀寫 float。

**回傳:**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

相機 FOV (0-180 度，視野)。 讀寫 float。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

相機縮放（以百分比表示的正值）。 讀寫 float。

**回傳:**  
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

相機縮放（以百分比表示的正值）。 讀寫 float。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標，以及圍繞該軸的旋轉來定義的。如果任一座標值為 Float.NaN，則所有旋轉皆未定義。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及圍繞該軸的旋轉來定義的。回傳陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。如果未定義旋轉，回傳 null。

**回傳:**  
float[]