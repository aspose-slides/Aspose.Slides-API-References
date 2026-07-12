---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: カメラを表します。
type: docs
url: /ja/com.aspose.slides/icamera/
---```
public interface ICamera
```

カメラを表します。
## メソッド

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | カメラタイプ 読み取り/書き込み [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [setCameraType(int value)](#setCameraType-int-) | カメラタイプ 読み取り/書き込み [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラ FOV (0-180 度、視野角) 読み取り/書き込み float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | カメラ FOV (0-180 度、視野角) 読み取り/書き込み float。 |
| [getZoom()](#getZoom--) | カメラズーム (正のパーセンテージ) 読み取り/書き込み float。 |
| [setZoom(float value)](#setZoom-float-) | カメラズーム (正のパーセンテージ) 読み取り/書き込み float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および緯度・経度座標を軸回転として使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および緯度・経度座標を軸回転として使用して回転が定義されます。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

カメラタイプ 読み取り/書き込み [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

カメラタイプ 読み取り/書き込み [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

カメラ FOV (0-180 度、視野角) 読み取り/書き込み float。

**戻り値:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

カメラ FOV (0-180 度、視野角) 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

カメラズーム (正のパーセンテージ) 読み取り/書き込み float。

**戻り値:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

カメラズーム (正のパーセンテージ) 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、および緯度・経度座標を軸回転として使用して回転が定義されます。座標値のいずれかが Float.NaN の場合、回転は未定義となります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| latitude | float | 緯度値 float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および緯度・経度座標を軸回転として使用して回転が定義されます。戻り配列の第1要素が緯度、第2要素が経度、第3要素が回転です。回転が定義されていない場合は null を返します。

**戻り値:**
float[] - 回転値の配列 (float[])。