---
title: IInnerShadow
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 内部シャドウ効果を表します。
type: docs
url: /ja/com.aspose.slides/iinnershadow/
---
**実装されているインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

内部シャドウ効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ぼかし半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ぼかし半径。 |
| [getDirection()](#getDirection--) | 影の方向。 |
| [setDirection(float value)](#setDirection-float-) | 影の方向。 |
| [getDistance()](#getDistance--) | 影の距離。 |
| [setDistance(double value)](#setDistance-double-) | 影の距離。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


ぼかし半径。 読み書き double.

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


ぼかし半径。 読み書き double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


影の方向。 読み書き float.

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


影の方向。 読み書き float.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


影の距離。 読み書き double.

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


影の距離。 読み書き double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


影の色。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)