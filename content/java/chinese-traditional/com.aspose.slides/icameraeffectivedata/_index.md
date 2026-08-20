---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變物件，包含有效的相機屬性。
type: docs
url: /zh-hant/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

不可變物件，包含有效的相機屬性。

--------------------

此介面用作 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) 的一部份。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | 相機類型。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機視野 (0-180 度，視場)。 |
| [getZoom()](#getZoom--) | 相機縮放（百分比的正值）。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標以及圍繞軸線的旋轉來定義的。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


相機類型。唯讀 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**回傳：**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


相機視野 (0-180 度，視場)。唯讀 float。

**回傳：**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


相機縮放（百分比的正值）。唯讀 float。

**回傳：**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


旋轉是透過使用緯度座標、經度座標以及圍繞軸線的旋轉來定義的。返回陣列的第一個元素 — 緯度，第二個 — 經度，第三個 — 旋轉。如果未定義旋轉，則返回 null。

**回傳：**
float[] - Array of rotation values as float[].