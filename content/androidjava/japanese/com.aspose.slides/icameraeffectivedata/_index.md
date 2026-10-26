---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 有効なカメラプロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

有効なカメラプロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) の一部として使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | カメラのタイプ。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラの視野角 (0-180 度、Field of View)。 |
| [getZoom()](#getZoom--) | カメラのズーム (パーセンテージでの正の値)。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および緯度・経度座標に対する軸回転を使用して定義される回転。 |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

カメラのタイプ。 読み取り専用 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

カメラの視野角 (0-180 度、Field of View)。 読み取り専用 float。

**戻り値:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

カメラのズーム (パーセンテージでの正の値)。 読み取り専用 float。

**戻り値:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および緯度・経度座標に対する軸回転を使用して定義される回転。 戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転数。 回転が定義されていない場合は null を返します。

**戻り値:**
float[] - 回転値の配列 (float[])。