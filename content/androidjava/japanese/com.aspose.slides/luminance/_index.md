---
title: Luminance
second_title: Android 用 Aspose.Slides の Java API リファレンス
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

Luminance エフェクトを表します。明るさはすべての色を白または黒に近づけるように線形にシフトします。コントラストはすべての色を互いに近づけたり離したりするようにスケーリングします。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getEffective()](#getEffective--) | 継承が適用された有効な Luminance エフェクトデータを取得します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された[Luminance](../../com.aspose.slides/luminance)が現在の[Luminance](../../com.aspose.slides/luminance)と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

継承が適用された有効な Luminance エフェクトデータを取得します。

**戻り値:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) のインスタンス。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された[Luminance](../../com.aspose.slides/luminance)が現在の[Luminance](../../com.aspose.slides/luminance)と等しいかどうかを判断します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の[Luminance](../../com.aspose.slides/luminance)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、それ以外の場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。