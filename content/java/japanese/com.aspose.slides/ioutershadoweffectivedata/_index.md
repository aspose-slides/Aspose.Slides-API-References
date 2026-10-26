---
title: IOuterShadowEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 外部シャドウ効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ioutershadoweffectivedata/
---
**実装されているインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IOuterShadowEffectiveData extends IEffectEffectiveData
```

外部シャドウ効果を表す不変オブジェクトです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径。 |
| [getDirection()](#getDirection--) | 影の方向。 |
| [getDistance()](#getDistance--) | 影の距離。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平スキュー角度を指定します（度単位）。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直スキュー角度を指定します（度単位）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | シェイプが回転した場合に、シャドウがシェイプとともに回転するかを指定します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 |
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

影の方向。 読み取り専用 float。

**戻り値:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

影の距離。 読み取り専用 double。

**戻り値:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

影の色。 読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
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

水平スキュー角度を指定します（度単位）。 読み取り専用 double。

**戻り値:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直スキュー角度を指定します（度単位）。 読み取り専用 double。

**戻り値:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

シェイプが回転した場合に、シャドウがシェイプとともに回転するかを指定します。 読み取り専用 boolean。

**戻り値:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 読み取り専用 double。

**戻り値:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。 読み取り専用 double。

**戻り値:**
double