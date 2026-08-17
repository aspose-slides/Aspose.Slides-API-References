---
title: AlphaCeiling
second_title: Aspose.Slides for Java API リファレンス
description: Alpha Ceiling エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphaceiling/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect  
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Alpha Ceiling エフェクトを表します。Alpha（不透明度）の値が 0 より大きい場合は 100% に変更されます。言い換えれば、部分的に不透明なものはすべて完全に不透明になります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Ceiling エフェクトデータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [AlphaCeiling](../../com.aspose.slides/alphaceiling) が現在の [AlphaCeiling](../../com.aspose.slides/alphaceiling) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

継承が適用された有効な Alpha Ceiling エフェクトデータを取得します。

**戻り値:**  
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) のインスタンス。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [AlphaCeiling](../../com.aspose.slides/alphaceiling) が現在の [AlphaCeiling](../../com.aspose.slides/alphaceiling) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [AlphaCeiling](../../com.aspose.slides/alphaceiling)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。