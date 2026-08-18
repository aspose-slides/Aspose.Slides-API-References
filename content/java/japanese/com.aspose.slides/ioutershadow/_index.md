---
title: IOuterShadow
second_title: Aspose.Slides の Java API リファレンス
description: 外側の影効果を表します。
type: docs
url: /ja/com.aspose.slides/ioutershadow/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

外側の影効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径（ポイント単位）。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径（ポイント単位）。 |
| [getDirection()](#getDirection--) | 影の方向（度単位）。 |
| [setDirection(float value)](#setDirection-float-) | 影の方向（度単位）。 |
| [getDistance()](#getDistance--) | オブジェクトから影までの距離（ポイント単位）。 |
| [setDistance(double value)](#setDistance-double-) | オブジェクトから影までの距離（ポイント単位）。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平のスキュー角度（度単位）。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平のスキュー角度（度単位）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直のスキュー角度（度単位）。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直のスキュー角度（度単位）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 影が図形と共に回転するかどうかを示します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 影が図形と共に回転するかどうかを示します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 元のサイズのパーセンテージで表した水平スケーリング係数。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 元のサイズのパーセンテージで表した水平スケーリング係数。 |
| [getScaleVertical()](#getScaleVertical--) | 元のサイズのパーセンテージで表した垂直スケーリング係数。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 元のサイズのパーセンテージで表した垂直スケーリング係数。 |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ぼかし半径（ポイント単位）。 既定値 - 0 pt。 読み取り/書き込み double。

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ぼかし半径（ポイント単位）。 既定値 - 0 pt。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

影の方向（度単位）。 既定値 - 0 � (left-to-right)。 読み取り/書き込み float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

影の方向（度単位）。 既定値 - 0 � (left-to-right)。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

オブジェクトから影までの距離（ポイント単位）。 既定値 - 0 pt。 読み取り/書き込み double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

オブジェクトから影までの距離（ポイント単位）。 既定値 - 0 pt。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

影の色。 既定値 - automatic black (theme-dependent)。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形の配置。 既定値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。 読み取り/書き込み [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形の配置。 既定値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。 読み取り/書き込み [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平のスキュー角度（度単位）。 既定値 - 0 �。 読み取り/書き込み double。

**戻り値:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

水平のスキュー角度（度単位）。 既定値 - 0 �。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直のスキュー角度（度単位）。 既定値 - 0 �。 読み取り/書き込み double。

**戻り値:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

垂直のスキュー角度（度単位）。 既定値 - 0 �。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

影が図形と共に回転するかどうかを示します。 既定値 - true。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

影が図形と共に回転するかどうかを示します。 既定値 - true。 読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

元のサイズのパーセンテージで表した水平スケーリング係数。 負のスケーリングは反転を引き起こします。 既定値 - 100 %。 読み取り/書き込み double。

**戻り値:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

元のサイズのパーセンテージで表した水平スケーリング係数。 負のスケーリングは反転を引き起こします。 既定値 - 100 %。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

元のサイズのパーセンテージで表した垂直スケーリング係数。 負のスケーリングは反転を引き起こします。 既定値 - 100 %。 読み取り/書き込み double。

**戻り値:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

元のサイズのパーセンテージで表した垂直スケーリング係数。 負のスケーリングは反転を引き起こします。 既定値 - 100 %。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |