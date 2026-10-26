---
title: IPresetShadow
second_title: Aspose.Slides for Java API リファレンス
description: プリセットシャドウ効果を表します。
type: docs
url: /ja/com.aspose.slides/ipresetshadow/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Preset シャドウ効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | シャドウの方向。 |
| [setDirection(float value)](#setDirection-float-) | シャドウの方向。 |
| [getDistance()](#getDistance--) | シャドウの距離。 |
| [setDistance(double value)](#setDistance-double-) | シャドウの距離。 |
| [getShadowColor()](#getShadowColor--) | シャドウの色。 |
| [getPreset()](#getPreset--) | プリセット。 |
| [setPreset(int value)](#setPreset-int-) | プリセット。 |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


シャドウの方向。読み書き可能 float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


シャドウの方向。読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


シャドウの距離。読み書き可能 double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


シャドウの距離。読み書き可能 double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


シャドウの色。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


プリセット。読み書き可能 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**戻り値:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


プリセット。読み書き可能 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |