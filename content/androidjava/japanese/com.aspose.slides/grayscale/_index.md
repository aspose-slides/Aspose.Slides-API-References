---
title: GrayScale
second_title: Aspose.Slides for Android の Java API リファレンス
description: Gray Scale エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/grayscale/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Gray Scale エフェクトを表します。すべてのエフェクトカラー値を、その輝度に対応するグレーの濃淡に変換します。エフェクトのアルファ (不透明度) 値は影響を受けません。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された効果的な Gray Scale エフェクト データを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [GrayScale](../../com.aspose.slides/grayscale) が現在の [GrayScale](../../com.aspose.slides/grayscale) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


継承が適用された効果的な Gray Scale エフェクト データを取得します。

**戻り値:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) のインスタンス。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [GrayScale](../../com.aspose.slides/grayscale) が現在の [GrayScale](../../com.aspose.slides/grayscale) と等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [GrayScale](../../com.aspose.slides/grayscale)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。