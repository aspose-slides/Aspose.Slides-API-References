---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: プリセットシャドウ効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ippresetshadoweffectivedata/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

プリセットシャドウ効果を表す不変オブジェクトです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | シャドウの方向。 |
| [getDistance()](#getDistance--) | シャドウの距離。 |
| [getShadowColor()](#getShadowColor--) | シャドウの色。 |
| [getPreset()](#getPreset--) | プリセット。 |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


シャドウの方向。 読み取り専用 float。

**戻り値:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


シャドウの距離。 読み取り専用 double。

**戻り値:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```


シャドウの色。 読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


プリセット。 読み取り専用 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**戻り値:**
int