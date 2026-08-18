---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Represents Camera.
type: docs
url: /ja/com.aspose.slides/icamera/
---```
public interface ICamera
```

カメラを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | カメラ タイプ 読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [setCameraType(int value)](#setCameraType-int-) | カメラ タイプ 読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラ FOV (0-180 度、視野角) 読み書き可能 float。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | カメラ FOV (0-180 度、視野角) 読み書き可能 float。 |
| [getZoom()](#getZoom--) | カメラ ズーム (正のパーセンテージ値) 読み書き可能 float。 |
| [setZoom(float value)](#setZoom-float-) | カメラ ズーム (正のパーセンテージ値) 読み書き可能 float。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および緯度と経度座標を軸回転として使用して回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および緯度と経度座標を軸回転として使用して回転が定義されます。 |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

カメラ タイプ 読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

カメラ タイプ 読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

カメラ FOV (0-180 度、視野角) 読み書き可能 float。

**戻り値:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

カメラ FOV (0-180 度、視野角) 読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

カメラ ズーム (正のパーセンテージ値) 読み書き可能 float。

**戻り値:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

カメラ ズーム (正のパーセンテージ値) 読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、および緯度と経度座標を軸回転として使用して回転が定義されます。いずれかの座標値が Float.NaN の場合、回転はすべて未定義となります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| latitude | float | 緯度値 |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および緯度と経度座標を軸回転として使用して回転が定義されます。戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転です。回転が定義されていない場合は null を返します。

**戻り値:**
float[] - 回転値を格納した float[] 配列。