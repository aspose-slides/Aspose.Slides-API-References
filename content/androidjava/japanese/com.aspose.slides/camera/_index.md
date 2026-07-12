---
title: Camera
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: Camera を表します。
type: docs
url: /ja/com.aspose.slides/camera/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

カメラを表します。

## メソッド

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | カメラタイプ。 |
| [setCameraType(int value)](#setCameraType-int-) | カメラタイプ。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラFOV（0〜180度、視野角）。 |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | カメラFOV（0〜180度、視野角）。 |
| [getZoom()](#getZoom--) | カメラズーム（パーセンテージでの正の値）。 |
| [setZoom(float value)](#setZoom-float-) | カメラズーム（パーセンテージでの正の値）。 |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | 緯度座標、経度座標、および緯度と経度座標を軸として回転させることで回転が定義されます。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および緯度と経度座標を軸として回転させることで回転が定義されます。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**  
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

カメラタイプ。読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

カメラタイプ。読み書き可能 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

カメラFOV（0〜180度、視野角）。読み書き可能 float。

**戻り値:**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

カメラFOV（0〜180度、視野角）。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

カメラズーム（パーセンテージでの正の値）。読み書き可能 float。

**戻り値:**  
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

カメラズーム（パーセンテージでの正の値）。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

緯度座標、経度座標、および緯度と経度座標を軸として回転させることで回転が定義されます。座標値のいずれかが Float.NaN の場合、回転は未定義となります。

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

緯度座標、経度座標、および緯度と経度座標を軸として回転させることで回転が定義されます。返却配列の最初の要素は緯度、2番目は経度、3番目は回転です。回転が定義されていない場合は null を返します。

**戻り値:**  
float[]