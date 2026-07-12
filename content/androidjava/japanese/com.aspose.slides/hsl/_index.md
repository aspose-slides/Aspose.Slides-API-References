---
title: HSL
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: Hue/Saturation/Luminance 効果を表します。
type: docs
url: /ja/com.aspose.slides/hsl/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect  
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Hue/Saturation/Luminance 効果を表します。hue、saturation、luminance はそれぞれ現在の値に対して相対的に調整できます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Hue/Saturation/Luminance 効果データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [HSL](../../com.aspose.slides/hsl) が現在の [HSL](../../com.aspose.slides/hsl) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

継承が適用された有効な Hue/Saturation/Luminance 効果データを取得します。

**戻り値:**  
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [HSL](../../com.aspose.slides/hsl) が現在の [HSL](../../com.aspose.slides/hsl) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [HSL](../../com.aspose.slides/hsl)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。