---
title: GrayScale
second_title: Aspose.Slides の Java API リファレンス
description: グレースケール効果を表します。
type: docs
url: /ja/com.aspose.slides/grayscale/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

グレースケール効果を表します。すべての効果カラー値を、その輝度に対応するグレーの色調に変換します。効果のアルファ（不透明度）値は影響を受けません。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効なグレースケール効果データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [GrayScale](../../com.aspose.slides/grayscale) が現在の [GrayScale](../../com.aspose.slides/grayscale) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |

### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


継承が適用された有効なグレースケール効果データを取得します。

**Returns:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [GrayScale](../../com.aspose.slides/grayscale) が現在の [GrayScale](../../com.aspose.slides/grayscale) と等しいかどうかを判断します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [GrayScale](../../com.aspose.slides/grayscale)。 |

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型のハッシュ関数として機能します。

**Returns:**
int - 現在のオブジェクトのハッシュコード。