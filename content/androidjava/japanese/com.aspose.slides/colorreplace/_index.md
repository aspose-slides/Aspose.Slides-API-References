---
title: ColorReplace
second_title: Aspose.Slides for Android の Java API リファレンス
description: Color Replacement エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/colorreplace/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Color Replacement エフェクトを表します。すべてのエフェクトカラーは固定色に変更されます。Alpha 値は影響を受けません。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor()](#getColor--) | すべてのピクセルの色を置き換えるカラー形式を返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な Color Replacement エフェクトデータを取得します。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [ColorReplace](../../com.aspose.slides/colorreplace) が現在の [ColorReplace](../../com.aspose.slides/colorreplace) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

すべてのピクセルの色を置き換えるカラー形式を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

継承が適用された有効な Color Replacement エフェクトデータを取得します。

**戻り値:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [ColorReplace](../../com.aspose.slides/colorreplace) が現在の [ColorReplace](../../com.aspose.slides/colorreplace) と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [ColorReplace](../../com.aspose.slides/colorreplace)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでなければ false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。