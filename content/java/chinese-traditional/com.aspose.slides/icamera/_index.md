---
title: ICamera
second_title: Aspose.Slides for Java API Reference
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
| [getCameraType()](#getCameraType--) | 相機類型 讀/寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [setCameraType(int value)](#setCameraType-int-) | 相機類型 讀/寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | 相機視野 (0-180 度, 視野) 讀/寫 float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | 相機視野 (0-180 度, 視野) 讀/寫 float。 |
| [getZoom()](#getZoom--) | 相機縮放 (正值，以百分比表示) 讀/寫 float。 |
| [setZoom(float value)](#setZoom-float-) | 相機縮放 (正值，以百分比表示) 讀/寫 float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，作為緯度與經度座標。 |
| [getRotation()](#getRotation--) | 旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，作為緯度與經度座標。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


相機類型 讀/寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**回傳值:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


相機類型 讀/寫 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


相機視野 (0-180 度, 視野) 讀/寫 float。

**回傳值:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


相機視野 (0-180 度, 視野) 讀/寫 float。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


相機縮放 (正值，以百分比表示) 讀/寫 float。

**回傳值:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


相機縮放 (正值，以百分比表示) 讀/寫 float。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，作為緯度與經度座標。如果任何座標值為 Float.NaN，則所有旋轉均未定義。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| latitude | float | 緯度值 float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


旋轉是透過使用緯度座標、經度座標，以及繞軸的旋轉來定義的，作為緯度與經度座標。返回陣列的第一個元素 – 緯度，第二個元素 – 經度，第三個元素 – 旋轉。如果未定義旋轉，則返回 null。

**回傳值:**
float[] - 旋轉值的陣列，類型為 float[]。