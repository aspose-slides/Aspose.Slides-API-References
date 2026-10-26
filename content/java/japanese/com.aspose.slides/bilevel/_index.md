---
title: BiLevel
second_title: Aspose.Slides for Java APIリファレンス
description: Bi-Level の黒/白エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/bilevel/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Bi-Level（黒/白）エフェクトを表します。指定されたしきい値未満の輝度を持つ入力色は黒に変更されます。指定された値以上の輝度を持つ入力色は白に設定されます。アルファ効果値はこのエフェクトの影響を受けません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Bi-Level エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [BiLevel](../../com.aspose.slides/bilevel) が現在の [BiLevel](../../com.aspose.slides/bilevel) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

継承が適用された有効な Bi-Level エフェクト データを取得します。

**戻り値:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [BiLevel](../../com.aspose.slides/bilevel) が現在の [BiLevel](../../com.aspose.slides/bilevel) と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [BiLevel](../../com.aspose.slides/bilevel)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュ コード。