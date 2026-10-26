---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API 參考文件
description: 包含有效相機屬性的不可變物件。
type: docs
url: /zh-hant/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

包含有效相機屬性的不可變物件。

--------------------

此介面用於 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部分。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相機類型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機視野 (0-180 度，視場角)。 |
| [getZoom()](#getZoom--) | 相機縮放 (正值，以百分比表示)。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及繞該軸的旋轉來定義的，緯度和經度座標即為如此。 |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

相機類型。唯讀 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**返回:**  
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

相機視野 (0-180 度，視場角)。唯讀 float。

**返回:**  
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

相機縮放 (正值，以百分比表示)。唯讀 float。

**返回:**  
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

旋轉是透過使用緯度座標、經度座標，以及繞該軸的旋轉來定義的。返回陣列的第一個元素 — 緯度，第二個 — 經度，第三個 — 旋轉。如未定義旋轉，則返回 null。

**返回:**  
float[] - 以 float[] 形式的旋轉值陣列。