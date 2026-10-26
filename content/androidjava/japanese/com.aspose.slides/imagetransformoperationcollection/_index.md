---
title: ImageTransformOperationCollection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 画像に適用されたエフェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/imagetransformoperationcollection/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)  
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

画像に適用されたエフェクトのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | コレクションからインデックスで[ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)を返します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコレクションから画像エフェクトを削除します。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 新しい Alpha Bi-Level エフェクトをコレクションの末尾に追加します。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 新しい Alpha Ceiling エフェクトをコレクションの末尾に追加します。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 新しい Alpha Floor エフェクトをコレクションの末尾に追加します。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 新しい Alpha Inverse エフェクトをコレクションの末尾に追加します。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 新しい Alpha Modulate エフェクトをコレクションの末尾に追加します。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 新しい Alpha Modulate Fixed エフェクトをコレクションの末尾に追加します。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 新しい Alpha Replace エフェクトをコレクションの末尾に追加します。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 新しい Bi-Level（黒/白）エフェクトをコレクションの末尾に追加します。 |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | 新しい Blur エフェクトをコレクションの末尾に追加します。 |
| [addColorChangeEffect()](#addColorChangeEffect--) | 新しい Color Change エフェクトをコレクションの末尾に追加します。 |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | 新しい Color Replacement エフェクトをコレクションの末尾に追加します。 |
| [addDuotoneEffect()](#addDuotoneEffect--) | 新しい Duotone エフェクトをコレクションの末尾に追加します。 |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | 新しい Fill Overlay エフェクトをコレクションの末尾に追加します。 |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | 新しい Gray Scale エフェクトをコレクションの末尾に追加します。 |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | 新しい Hue/Saturation/Luminance エフェクトをコレクションの末尾に追加します。 |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | 新しい Luminance エフェクトをコレクションの末尾に追加します。 |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | 新しい Tint エフェクトをコレクションの末尾に追加します。 |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | 新しい BrightnessContrast エフェクトをコレクションの末尾に追加します。 |
| [size()](#size--) | コレクション内の画像エフェクトの数を返します。 |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを示す値を取得します。 |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | 新しい画像エフェクトをコレクションの末尾に追加します。 |
| [clear()](#clear--) | コレクションからすべての画像エフェクトを削除します。 |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判定します。 |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | 特定の配列インデックスから開始して、[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を配列にコピーします。 |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | 特定のオブジェクトの最初の出現を[IGenericCollection](../../com.aspose.slides/igenericcollection)から削除します。 |
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**返り値:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

コレクションからインデックスで[ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**返り値:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) オブジェクト。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

指定されたインデックスのコレクションから画像エフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除する画像エフェクトのインデックス。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

新しい Alpha Bi-Level エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | アルファ バイレベル効果の閾値。 |

**返り値:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

新しい Alpha Ceiling エフェクトをコレクションの末尾に追加します。

**返り値:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

新しい Alpha Floor エフェクトをコレクションの末尾に追加します。

**返り値:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

新しい Alpha Inverse エフェクトをコレクションの末尾に追加します。

**返り値:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

新しい Alpha Modulate エフェクトをコレクションの末尾に追加します。

**返り値:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

新しい Alpha Modulate Fixed エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| amount | float | アルファをスケーリングする割合。 |

**返り値:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

新しい Alpha Replace エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | float | 新しい不透明度の値。 |

**返り値:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - コレクション内の新しい画像エフェクトのインデックス。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

新しい Bi-Level（黒/白）エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | Bi-Level 効果の輝度閾値。閾値以上は白、未満は黒に設定されます。 |

**返り値:**
[IBiLevel](../../com.aspose.slides/ibilevel) - コレクション内の新しい画像エフェクトのインデックス。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

新しい Blur エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| radius | double | ぼかしの半径。 |
| grow | boolean | ぼかしに伴ってオブジェクトの境界を拡張するかどうか。true は拡張、false は拡張しません。 |

**返り値:**
[IBlur](../../com.aspose.slides/iblur) - コレクション内の新しい画像エフェクトのインデックス。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

新しい Color Change エフェクトをコレクションの末尾に追加します。

**返り値:**
[IColorChange](../../com.aspose.slides/icolorchange) - コレクション内の新しい画像エフェクトのインデックス。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

新しい Color Replacement エフェクトをコレクションの末尾に追加します。

**返り値:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - コレクション内の新しい画像エフェクトのインデックス。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

新しい Duotone エフェクトをコレクションの末尾に追加します。

**返り値:**
[IDuotone](../../com.aspose.slides/iduotone) - コレクション内の新しい画像エフェクトのインデックス。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

新しい Fill Overlay エフェクトをコレクションの末尾に追加します。

**返り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - コレクション内の新しい画像エフェクトのインデックス。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

新しい Gray Scale エフェクトをコレクションの末尾に追加します。

**返り値:**
[IGrayScale](../../com.aspose.slides/igrayscale) - コレクション内の新しい画像エフェクトのインデックス。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

新しい Hue/Saturation/Luminance エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相を調整する度数。 |
| saturation | float | 彩度を調整する割合。 |
| luminance | float | 輝度を調整する割合。 |

**返り値:**
[IHSL](../../com.aspose.slides/ihsl) - コレクション内の新しい画像エフェクトのインデックス。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

新しい Luminance エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**返り値:**
[ILuminance](../../com.aspose.slides/iluminance) - コレクション内の新しい画像エフェクトのインデックス。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

新しい Tint エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相 (トーン) を指定します。 |
| amount | float | 色のシフト量を指定します。 |

**返り値:**
[ITint](../../com.aspose.slides/itint) - コレクション内の新しい画像エフェクトのインデックス。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

新しい BrightnessContrast エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**返り値:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - コレクション内の新しい画像エフェクトのインデックス。

### size() {#size--}
```
public final int size()
```

コレクション内の画像エフェクトの数を返します。読み取り専用 int 。

**返り値:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用かどうかを取得します。読み取り専用 boolean。

**返り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) が読み取り専用の場合は true、そうでない場合は false。

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

新しい画像エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

[IGenericCollection](../../com.aspose.slides/igenericcollection) が特定の値を含むかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) 内で検索するオブジェクト。 |

**返り値:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) にアイテムが見つかった場合は true、見つからなければ false。

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) の要素を特定の配列インデックスから開始して配列にコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) からコピーされた要素の宛先となる一次元配列。配列は 0 ベースのインデックスを持つ必要があります。 |
| arrayIndex | int | コピー開始位置の配列内ゼロベースインデックス。 |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) から特定のオブジェクトの最初の出現を削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) から削除するオブジェクト。 |

**返り値:**
boolean - アイテムが [IGenericCollection](../../com.aspose.slides/igenericcollection) から正常に削除された場合は true、そうでない場合は false。元の [IGenericCollection](../../com.aspose.slides/igenericcollection) にアイテムが見つからなかった場合も false を返します。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

コレクションを反復する列挙子を返します。

**返り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - コレクションを反復できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

コレクション全体の java イテレータを返します。

**返り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator for the entire collection.