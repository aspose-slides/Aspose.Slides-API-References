---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /zh-hant/com.aspose.slides/icamera/
---```
public interface ICamera
```

表示相機。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相機類型 可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [setCameraType(int value)](#setCameraType-int-) | 相機類型 可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機 FOV (0-180 deg, field of View) 可讀寫 float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相機 FOV (0-180 deg, field of View) 可讀寫 float。 |
| [getZoom()](#getZoom--) | 相機縮放 (正值為百分比) 可讀寫 float。 |
| [setZoom(float value)](#setZoom-float-) | 相機縮放 (正值為百分比) 可讀寫 float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，緯度與經度座標即為該軸的旋轉。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，緯度與經度座標即為該軸的旋轉。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相機類型 可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回值:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

相機類型 可讀寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相機 FOV (0-180 deg, field of View) 可讀寫 float。

**返回值:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

相機 FOV (0-180 deg, field of View) 可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相機縮放 (正值為百分比) 可讀寫 float。

**返回值:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

相機縮放 (正值為百分比) 可讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，緯度與經度座標即為該軸的旋轉。如果任一座標值為 Float.NaN，則所有旋轉皆未定義。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| latitude | float | 緯度值 float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，緯度與經度座標即為該軸的旋轉。返回陣列的第一個元素為緯度，第二個為經度，第三個為旋轉。如果未定義旋轉，則返回 null。

**返回值:**
float[] - 旋轉值陣列，以 float[] 形式。