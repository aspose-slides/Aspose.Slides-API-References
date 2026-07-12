---
title: BiLevel
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: Bi-Levelの黒/白効果を表します。
type: docs
url: /ja/com.aspose.slides/bilevel/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Bi-Level（黒/白）効果を表します。指定された閾値未満の輝度を持つ入力色は黒に変換され、閾値以上の輝度を持つ入力色は白に設定されます。この効果ではアルファ効果値は影響を受けません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された効果的な Bi-Level 効果データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [BiLevel](../../com.aspose.slides/bilevel) が現在の [BiLevel](../../com.aspose.slides/bilevel) と等しいかどうかを判定します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

継承が適用された効果的な Bi-Level 効果データを取得します。

**戻り値:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [BiLevel](../../com.aspose.slides/bilevel) が現在の [BiLevel](../../com.aspose.slides/bilevel) と等しいかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [BiLevel](../../com.aspose.slides/bilevel)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。