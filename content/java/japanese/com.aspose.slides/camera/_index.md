---
title: Camera
second_title: Aspose.Slides の Java 用 API リファレンス
description: Camera を表します。
type: docs
url: /ja/com.aspose.slides/camera/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Camera を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | カメラのタイプ。 |
| [setCameraType(int value)](#setCameraType-int-) | カメラのタイプ。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラ FOV (0-180 度、視野角)。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | カメラ FOV (0-180 度、視野角)。 |
| [getZoom()](#getZoom--) | カメラ ズーム (パーセンテージの正の値)。 |
| [setZoom(float value)](#setZoom-float-) | カメラ ズーム (パーセンテージの正の値)。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および緯度と経度座標として軸まわりの回転を使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および緯度と経度座標として軸まわりの回転を使用して回転が定義されます。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```


バージョン。読み取り専用 long。

**戻り値:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


カメラのタイプ。読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


カメラのタイプ。読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


カメラ FOV (0-180 度、視野角)。読み書き可能 float。

**戻り値:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


カメラ FOV (0-180 度、視野角)。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```


カメラ ズーム (パーセンテージの正の値)。読み書き可能 float。

**戻り値:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


カメラ ズーム (パーセンテージの正の値)。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


緯度座標、経度座標、および緯度と経度座標として軸まわりの回転を使用して回転が定義されます。座標値のいずれかが Float.NaN の場合、すべての回転は未定義になります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


緯度座標、経度座標、および緯度と経度座標として軸まわりの回転を使用して回転が定義されます。戻り配列の最初の要素は latitude、2 番目は longitude、3 番目は revolution です。回転が定義されていない場合は null を返します。

**戻り値:**
float[]