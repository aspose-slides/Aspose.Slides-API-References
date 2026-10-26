---
title: IOuterShadow
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 外側の影効果を表します。
type: docs
url: /ja/com.aspose.slides/ioutershadow/
---
**すべての実装済みインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

外側の影効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ポイント単位のぼかし半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ポイント単位のぼかし半径。 |
| [getDirection()](#getDirection--) | 角度単位の影の方向。 |
| [setDirection(float value)](#setDirection-float-) | 角度単位の影の方向。 |
| [getDistance()](#getDistance--) | オブジェクトから影までの距離（ポイント単位）。 |
| [setDistance(double value)](#setDistance-double-) | オブジェクトから影までの距離（ポイント単位）。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平せん断角度（度単位）。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平せん断角度（度単位）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直せん断角度（度単位）。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直せん断角度（度単位）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 影が形状と共に回転するかどうかを示します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 影が形状と共に回転するかどうかを示します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 元のサイズに対するパーセンテージでの水平スケーリング係数。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 元のサイズに対するパーセンテージでの水平スケーリング係数。 |
| [getScaleVertical()](#getScaleVertical--) | 元のサイズに対するパーセンテージでの垂直スケーリング係数。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 元のサイズに対するパーセンテージでの垂直スケーリング係数。 |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ポイント単位のぼかし半径。デフォルト値 - 0 pt。読み書き可能 double。

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ポイント単位のぼかし半径。デフォルト値 - 0 pt。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

角度単位の影の方向。デフォルト値 - 0 � (左から右)。読み書き可能 float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

角度単位の影の方向。デフォルト値 - 0 � (左から右)。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

オブジェクトから影までの距離（ポイント単位）。デフォルト値 - 0 pt。読み書き可能 double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

オブジェクトから影までの距離（ポイント単位）。デフォルト値 - 0 pt。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

影の色。デフォルト値 - 自動黒（テーマ依存）。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形の配置。デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。読み書き可能 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形の配置。デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。読み書き可能 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平せん断角度（度単位）。デフォルト値 - 0 �。読み書き可能 double。

**戻り値:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

水平せん断角度（度単位）。デフォルト値 - 0 �。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直せん断角度（度単位）。デフォルト値 - 0 �。読み書き可能 double。

**戻り値:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

垂直せん断角度（度単位）。デフォルト値 - 0 �。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

影が形状と共に回転するかどうかを示します。デフォルト値 - true。読み書き可能 boolean。

**戻り値:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

影が形状と共に回転するかどうかを示します。デフォルト値 - true。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

元のサイズに対するパーセンテージでの水平スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 - 100 %。読み書き可能 double。

**戻り値:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

元のサイズに対するパーセンテージでの水平スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 - 100 %。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

元のサイズに対するパーセンテージでの垂直スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 - 100 %。読み書き可能 double。

**戻り値:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

元のサイズに対するパーセンテージでの垂直スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 - 100 %。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |