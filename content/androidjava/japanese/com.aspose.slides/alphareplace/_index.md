---
title: AlphaReplace
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: Alpha Replace エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/alphareplace/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect
```
public final class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

Alpha Replace エフェクトを表します。エフェクトのアルファ（不透明度）値は固定のアルファに置き換えられます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Alpha Replace エフェクトデータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された[AlphaReplace](../../com.aspose.slides/alphareplace)が現在の[AlphaReplace](../../com.aspose.slides/alphareplace)と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```

継承が適用された有効な Alpha Replace エフェクトデータを取得します。

**戻り値:**
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - [IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) のインスタンス。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された[AlphaReplace](../../com.aspose.slides/alphareplace)が現在の[AlphaReplace](../../com.aspose.slides/alphareplace)と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の[AlphaReplace](../../com.aspose.slides/alphareplace)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。