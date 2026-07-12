---
title: Tint
second_title: Aspose.Slides for Android の Java API リファレンス
description: Tint効果を表します。
type: docs
url: /ja/com.aspose.slides/tint/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**すべての実装インターフェイス:**  
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect  
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

Tint効果を表します。指定された量だけ色相に向かって/離れて効果の色値をシフトします。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Tint 効果データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [Tint](../../com.aspose.slides/tint) が現在の [Tint](../../com.aspose.slides/tint) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```

継承が適用された有効な Tint 効果データを取得します。

**戻り値:**  
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - A [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [Tint](../../com.aspose.slides/tint) が現在の [Tint](../../com.aspose.slides/tint) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較する[Tint](../../com.aspose.slides/tint)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型のハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。