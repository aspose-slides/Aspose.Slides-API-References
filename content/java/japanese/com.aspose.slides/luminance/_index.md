---
title: Luminance
second_title: Aspose.Slides for Java API リファレンス
description: Luminance エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/luminance/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect  
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminance エフェクトを表します。Brightness はすべての色を白または黒に近づけるように線形にシフトします。Contrast はすべての色をより近く、または遠くなるようにスケールします。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Luminance エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [Luminance](../../com.aspose.slides/luminance) が現在の [Luminance](../../com.aspose.slides/luminance) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

継承が適用された有効な Luminance エフェクト データを取得します。

**戻り値:**  
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - A [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [Luminance](../../com.aspose.slides/luminance) が現在の [Luminance](../../com.aspose.slides/luminance) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較する [Luminance](../../com.aspose.slides/luminance)。 |

**戻り値:**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**  
int - 現在のオブジェクトのハッシュコード。