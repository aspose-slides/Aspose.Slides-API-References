---
title: PresetShadow
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プリセットシャドウ効果を表します。
type: docs
url: /ja/com.aspose.slides/presetshadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a Preset Shadow effect.
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDirection()](#getDirection--) | 影の方向。 |
| [setDirection(float value)](#setDirection-float-) | 影の方向。 |
| [getDistance()](#getDistance--) | 影の距離。 |
| [setDistance(double value)](#setDistance-double-) | 影の距離。 |
| [getShadowColor()](#getShadowColor--) | 影の色。 |
| [getPreset()](#getPreset--) | プリセット。 |
| [setPreset(int value)](#setPreset-int-) | プリセット。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なプリセットシャドウ効果データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [PresetShadow](../../com.aspose.slides/presetshadow) が現在の [PresetShadow](../../com.aspose.slides/presetshadow) と等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

影の方向。読み書き可能  float .

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

影の方向。読み書き可能  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

影の距離。読み書き可能  double .

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

影の距離。読み書き可能  double .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

影の色。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

プリセット。読み書き可能 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**戻り値:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

プリセット。読み書き可能 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

継承が適用された有効なプリセットシャドウ効果データを取得します。

**戻り値:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [PresetShadow](../../com.aspose.slides/presetshadow) が現在の [PresetShadow](../../com.aspose.slides/presetshadow) と等しいかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [PresetShadow](../../com.aspose.slides/presetshadow)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、それ以外は false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。