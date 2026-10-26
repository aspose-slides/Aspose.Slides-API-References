---
title: IReflection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 反射効果を表します。
type: docs
url: /ja/com.aspose.slides/ireflection/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

反射効果を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 開始アルファ値（パーセント）の開始位置（アルファ グラデーション ランプに沿って）を指定します。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 開始アルファ値（パーセント）の開始位置（アルファ グラデーション ランプに沿って）を指定します。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 終了アルファ値（パーセント）の終了位置（アルファ グラデーション ランプに沿って）を指定します。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 終了アルファ値（パーセント）の終了位置（アルファ グラデーション ランプに沿って）を指定します。 |
| [getFadeDirection()](#getFadeDirection--) | 反射のオフセット方向を指定します。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 反射のオフセット方向を指定します。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 開始反射不透明度。 |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 開始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 終了反射不透明度。 |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 終了反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径。 |
| [getDirection()](#getDirection--) | 反射の方向。 |
| [setDirection(float value)](#setDirection-float-) | 反射の方向。 |
| [getDistance()](#getDistance--) | 反射の距離。 |
| [setDistance(double value)](#setDistance-double-) | 反射の距離。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平せん断角度を指定します。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平せん断角度を指定します。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直せん断角度を指定します。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直せん断角度を指定します。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | シェイプが回転した場合に、反射もシェイプと共に回転するかどうかを指定します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | シェイプが回転した場合に、反射もシェイプと共に回転するかどうかを指定します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

開始アルファ値（パーセント）の開始位置（アルファ グラデーション ランプに沿って）を指定します。 読み取り/書き込み float。

**戻り値:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

開始アルファ値（パーセント）の開始位置（アルファ グラデーション ランプに沿って）を指定します。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

終了アルファ値（パーセント）の終了位置（アルファ グラデーション ランプに沿って）を指定します。 読み取り/書き込み float。

**戻り値:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

終了アルファ値（パーセント）の終了位置（アルファ グラデーション ランプに沿って）を指定します。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

反射のオフセット方向を指定します。（角度） 読み取り/書き込み float。

**戻り値:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

反射のオフセット方向を指定します。（角度） 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

開始反射不透明度。（パーセント） 読み取り/書き込み float。

**戻り値:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

開始反射不透明度。（パーセント） 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

終了反射不透明度。（パーセント） 読み取り/書き込み float。

**戻り値:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

終了反射不透明度。（パーセント） 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ぼかし半径。 読み取り/書き込み double。

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

ぼかし半径。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

反射の方向。 読み取り/書き込み float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

反射の方向。 読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

反射の距離。 読み取り/書き込み double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

反射の距離。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形の配置。 読み取り/書き込み [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形の配置。 読み取り/書き込み [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平せん断角度を指定します。 読み取り/書き込み double。

**戻り値:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

水平せん断角度を指定します。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直せん断角度を指定します。 読み取り/書き込み double。

**戻り値:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

垂直せん断角度を指定します。 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

シェイプが回転した場合に、反射もシェイプと共に回転するかどうかを指定します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

シェイプが回転した場合に、反射もシェイプと共に回転するかどうかを指定します。 読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り/書き込み double。

**戻り値:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り/書き込み double。

**戻り値:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |