---
title: IReflectionEffectiveData
second_title: Java API リファレンスによる Aspose.Slides for Android
description: Reflection 効果を表す不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/ireflectioneffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Reflection 効果を表す不変オブジェクト。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | アルファ グラデーション ランプに沿った開始アルファ値（パーセント）の開始位置を指定します。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | アルファ グラデーション ランプに沿った終了アルファ値（パーセント）の終了位置を指定します。 |
| [getFadeDirection()](#getFadeDirection--) | 反射のオフセット方向を指定します。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 開始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 終了反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径。 |
| [getDirection()](#getDirection--) | 反射の方向。 |
| [getDistance()](#getDistance--) | 反射の距離。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平せっ斜角度を指定します。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直せっ斜角度を指定します。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 形状が回転した場合に、反射が形状とともに回転するかどうかを指定します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

開始アルファ値（パーセント）の開始位置を、アルファ グラデーション ランプに沿って指定します。 読み取り専用 float。

**戻り値:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

終了アルファ値（パーセント）の終了位置を、アルファ グラデーション ランプに沿って指定します。 読み取り専用 float。

**戻り値:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

反射のオフセット方向（角度）を指定します。 読み取り専用 float。

**戻り値:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

開始反射不透明度（パーセント）。 読み取り専用 float。

**戻り値:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

終了反射不透明度（パーセント）。 読み取り専用 float。

**戻り値:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

ぼかし半径。 読み取り専用 double。

**戻り値:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

反射の方向。 読み取り専用 float。

**戻り値:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

反射の距離。 読み取り専用 double。

**戻り値:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形の配置。 読み取り専用 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平せっ斜角度を指定します。 読み取り専用 double。

**戻り値:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直せっ斜角度を指定します。 読み取り専用 double。

**戻り値:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

形状が回転した場合に、反射が形状とともに回転するかどうかを指定します。 読み取り専用 boolean。

**戻り値:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り専用 double。

**戻り値:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント） 読み取り専用 double。

**戻り値:**
double