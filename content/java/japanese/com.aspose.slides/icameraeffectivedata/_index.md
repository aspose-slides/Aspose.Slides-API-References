---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: 有効なカメラ プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

有効なカメラ プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) の一部として使用されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCameraType()](#getCameraType--) | カメラの種類。 |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | カメラの視野角 (0-180 度、field of View)。 |
| [getZoom()](#getZoom--) | カメラズーム (パーセンテージでの正の値)。 |
| [getRotation()](#getRotation--) | 緯度座標、経度座標、および軸周りの回転で回転が定義されます。 |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

カメラの種類。読み取り専用 [CameraPresetType](../../com.aspose.slides/camerapresettype)。

**戻り値:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

カメラの視野角 (0-180 度、field of View)。読み取り専用 float。

**戻り値:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

カメラズーム (パーセンテージでの正の値)。読み取り専用 float。

**戻り値:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

緯度座標、経度座標、および軸周りの回転で回転が定義されます。戻り配列の最初の要素は緯度、2 番目は経度、3 番目は回転です。定義された回転がない場合は null を返します。

**戻り値:**
float[] - 回転値の配列 (float[])。