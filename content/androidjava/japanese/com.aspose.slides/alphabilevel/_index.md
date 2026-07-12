---
title: AlphaBiLevel
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Alpha Bi-Level エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphabilevel/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha（Opacity）値は 0（完全に透明）に、しきい値以上の Alpha 値は 100%（完全に不透明）に変換されます。

## メソッド

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | エフェクトのしきい値を返します。 |
| [setThreshold(float value)](#setThreshold-float-) | エフェクトのしきい値を返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Bi-Level エフェクトデータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaBiLevel](../../com.aspose.slides/alphabilevel) が現在の [AlphaBiLevel](../../com.aspose.slides/alphabilevel) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

エフェクトのしきい値を返します。読み書き float。

**戻り値:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

エフェクトのしきい値を返します。読み書き float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

継承が適用された有効な Alpha Bi-Level エフェクトデータを取得します。

**戻り値:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [AlphaBiLevel](../../com.aspose.slides/alphabilevel) が現在の [AlphaBiLevel](../../com.aspose.slides/alphabilevel) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較する [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。