---
title: AlphaBiLevel
second_title: Aspose.Slides の Java API リファレンス
description: Alpha Bi-Level エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphabilevel/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level エフェクトを表します。閾値未満の Alpha (不透明度) の値は 0 (完全に透明) に、閾値以上の Alpha の値は 100% (完全に不透明) に変更されます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 効果の閾値を返します。 |
| [setThreshold(float value)](#setThreshold-float-) | 効果の閾値を返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Bi-Level エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaBiLevel](../../com.aspose.slides/alphabilevel) が現在の [AlphaBiLevel](../../com.aspose.slides/alphabilevel) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

効果の閾値を返します。読み取り/書き込み float。

**戻り値:**  
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

効果の閾値を返します。読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

継承が適用された有効な Alpha Bi-Level エフェクト データを取得します。

**戻り値:**  
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [AlphaBiLevel](../../com.aspose.slides/alphabilevel) が現在の [AlphaBiLevel](../../com.aspose.slides/alphabilevel) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでなければ false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。