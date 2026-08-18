---
title: ImageTransformOperationCollection
second_title: Aspose.Slides for Java API リファレンス
description: 画像に適用されたエフェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imagetransformoperationcollection/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```java
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

画像に適用されるエフェクトのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | コレクションからインデックスで [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) を返します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコレクションから画像エフェクトを削除します。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | コレクションの末尾に新しい Alpha Bi-Level エフェクトを追加します。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | コレクションの末尾に新しい Alpha Ceiling エフェクトを追加します。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | コレクションの末尾に新しい Alpha Floor エフェクトを追加します。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | コレクションの末尾に新しい Alpha Inverse エフェクトを追加します。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | コレクションの末尾に新しい Alpha Modulate エフェクトを追加します。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | コレクションの末尾に新しい Alpha Modulate Fixed エフェクトを追加します。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | コレクションの末尾に新しい Alpha Replace エフェクトを追加します。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | コレクションの末尾に新しい Bi-Level (black/white) エフェクトを追加します。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | コレクションの末尾に新しい Blur エフェクトを追加します。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | コレクションの末尾に新しい Color Change エフェクトを追加します。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | コレクションの末尾に新しい Color Replacement エフェクトを追加します。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | コレクションの末尾に新しい Duotone エフェクトを追加します。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | コレクションの末尾に新しい Fill Overlay エフェクトを追加します。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | コレクションの末尾に新しい Gray Scale エフェクトを追加します。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | コレクションの末尾に新しい Hue/Saturation/Luminance エフェクトを追加します。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | コレクションの末尾に新しい Luminance エフェクトを追加します。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | コレクションの末尾に新しい Tint エフェクトを追加します。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | コレクションの末尾に新しい BrightnessContrast エフェクトを追加します。 |
| [size()](#size--) | コレクション内の画像エフェクトの数を返します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | コレクションの末尾に新しい画像エフェクトを追加します。 |
| [clear()](#clear--) | コレクションからすべての画像エフェクトを削除します。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long。

**戻り値:**
long
### get_Item(int index) {#get-Item-int-}
```java
public final IImageTransformOperation get_Item(int index)
```

インデックスでコレクションから [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) を返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) オブジェクト。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのコレクションから画像エフェクトを削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除すべき画像エフェクトのインデックス。 |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

コレクションの末尾に新しい Alpha Bi-Level エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level エフェクトのしきい値。 |

**戻り値:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

コレクションの末尾に新しい Alpha Ceiling エフェクトを追加します。

**戻り値:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

コレクションの末尾に新しい Alpha Floor エフェクトを追加します。

**戻り値:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

コレクションの末尾に新しい Alpha Inverse エフェクトを追加します。

**戻り値:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

コレクションの末尾に新しい Alpha Modulate エフェクトを追加します。

**戻り値:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

コレクションの末尾に新しい Alpha Modulate Fixed エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | アルファをスケールするパーセンテージ。 |

**戻り値:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - コレクション内の新しい画像エフェクトのインデックス。
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

コレクションの末尾に新しい Alpha Replace エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | 新しい不透明度の値。 |

**戻り値:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - コレクション内の新しい画像エフェクトのインデックス。
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

コレクションの末尾に新しい Bi-Level (black/white) エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Bi-Level エフェクトの明度しきい値。しきい値以上は白、未満は黒に設定されます。 |

**戻り値:**
[IBiLevel](../../com.aspose.slides/ibilevel) - コレクション内の新しい画像エフェクトのインデックス。
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

コレクションの末尾に新しい Blur エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | ぼかしの半径。 |
| grow | boolean | ぼかしの結果としてオブジェクトの境界を拡大するかどうかを指定します。true は拡大、false は拡大しません。 |

**戻り値:**
[IBlur](../../com.aspose.slides/iblur) - コレクション内の新しい画像エフェクトのインデックス。
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

コレクションの末尾に新しい Color Change エフェクトを追加します。

**戻り値:**
[IColorChange](../../com.aspose.slides/icolorchange) - コレクション内の新しい画像エフェクトのインデックス。
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

コレクションの末尾に新しい Color Replacement エフェクトを追加します。

**戻り値:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - コレクション内の新しい画像エフェクトのインデックス。
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

コレクションの末尾に新しい Duotone エフェクトを追加します。

**戻り値:**
[IDuotone](../../com.aspose.slides/iduotone) - コレクション内の新しい画像エフェクトのインデックス。
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

コレクションの末尾に新しい Fill Overlay エフェクトを追加します。

**戻り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - コレクション内の新しい画像エフェクトのインデックス。
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

コレクションの末尾に新しい Gray Scale エフェクトを追加します。

**戻り値:**
[IGrayScale](../../com.aspose.slides/igrayscale) - コレクション内の新しい画像エフェクトのインデックス。
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

コレクションの末尾に新しい Hue/Saturation/Luminance エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 色相を調整する度数。 |
| saturation | float | 彩度を調整するパーセンテージ。 |
| luminance | float | 明度を調整するパーセンテージ。 |

**戻り値:**
[IHSL](../../com.aspose.slides/ihsl) - コレクション内の新しい画像エフェクトのインデックス。
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

コレクションの末尾に新しい Luminance エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**戻り値:**
[ILuminance](../../com.aspose.slides/iluminance) - コレクション内の新しい画像エフェクトのインデックス。
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

コレクションの末尾に新しい Tint エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | 色合いの方向。 |
| amount | float | 色の値がどれだけシフトするかを指定します。 |

**戻り値:**
[ITint](../../com.aspose.slides/itint) - コレクション内の新しい画像エフェクトのインデックス。
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

コレクションの末尾に新しい BrightnessContrast エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**戻り値:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - コレクション内の新しい画像エフェクトのインデックス。
### size() {#size--}
```
public final int size()
```

コレクション内の画像エフェクトの数を返します。読み取り専用 int 。

**戻り値:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを取得します。読み取り専用 boolean。

**戻り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true、そうでない場合は false。
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

コレクションの末尾に新しい画像エフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | コレクションの末尾に追加する画像エフェクト。 |
### clear() {#clear--}
```
public final void clear()
```

コレクションからすべての画像エフェクトを削除します。
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判断します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**戻り値:**
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) に見つかった場合は true、それ以外は false。
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーし、特定の配列インデックスから開始します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の格納先となる一次元配列。配列はゼロベースインデックスである必要があります。 |
| arrayIndex | int | コピーを開始する配列内のゼロベースインデックス。 |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**戻り値:**
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) から正常に削除された場合は true、そうでない場合は false。元の [IGenericCollection](../../com.aspose.slides/igenericcollection) にアイテムが見つからなかった場合も false を返します。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - コレクションを反復処理できる IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - コレクション全体の java.util.Iterator。