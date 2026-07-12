---
title: IImageTransformOperationCollection
second_title: Java API リファレンスによる Aspose.Slides for Android
description: 画像に適用されるエフェクトのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/iimagetransformoperationcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

画像に適用されるエフェクトのコレクションを表します。

## メソッド

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | コレクションからインデックスで [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) を返します。 |
| [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのコレクションから画像エフェクトを削除します。 |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | 新しい Alpha Bi-Level エフェクトをコレクションの末尾に追加します。 |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | 新しい Alpha Ceiling エフェクトをコレクションの末尾に追加します。 |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | 新しい Alpha Floor エフェクトをコレクションの末尾に追加します。 |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | 新しい Alpha Inverse エフェクトをコレクションの末尾に追加します。 |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | 新しい Alpha Modulate エフェクトをコレクションの末尾に追加します。 |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | 新しい Alpha Modulate Fixed エフェクトをコレクションの末尾に追加します。 |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | 新しい Alpha Replace エフェクトをコレクションの末尾に追加します。 |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | 新しい Bi-Level (黒/白) エフェクトをコレクションの末尾に追加します。 |
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

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

コレクションからインデックスで [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | アイテムのインデックス。 |

**戻り値:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) オブジェクト。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

指定されたインデックスのコレクションから画像エフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除すべき画像エフェクトのインデックス。 |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

新しい Alpha Bi-Level エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level エフェクトのしきい値。 |

**戻り値:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

新しい Alpha Ceiling エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

新しい Alpha Floor エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

新しい Alpha Inverse エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

新しい Alpha Modulate エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

新しい Alpha Modulate Fixed エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| amount | float | アルファをスケーリングするパーセンテージ。 |

**戻り値:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - コレクション内の新しい画像エフェクトのインデックス。

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

新しい Alpha Replace エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | float | 新しい不透明度の値。 |

**戻り値:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - コレクション内の新しい画像エフェクトのインデックス。

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

新しい Bi-Level (黒/白) エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | Bi-Level エフェクトの輝度しきい値。しきい値以上は白に、未満は黒に設定されます。 |

**戻り値:**
[IBiLevel](../../com.aspose.slides/ibilevel) - コレクション内の新しい画像エフェクトのインデックス。

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

新しい Blur エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| radius | double | ぼかしの半径。 |
| grow | boolean | ぼかしの結果としてオブジェクトの境界を拡大するかどうかを指定します。true は境界が拡大され、false は拡大されません。 |

**戻り値:**
[IBlur](../../com.aspose.slides/iblur) - コレクション内の新しい画像エフェクトのインデックス。

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

新しい Color Change エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IColorChange](../../com.aspose.slides/icolorchange) - コレクション内の新しい画像エフェクトのインデックス。

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

新しい Color Replacement エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - コレクション内の新しい画像エフェクトのインデックス。

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

新しい Duotone エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IDuotone](../../com.aspose.slides/iduotone) - コレクション内の新しい画像エフェクトのインデックス。

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

新しい Fill Overlay エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - コレクション内の新しい画像エフェクトのインデックス。

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

新しい Gray Scale エフェクトをコレクションの末尾に追加します。

**戻り値:**
[IGrayScale](../../com.aspose.slides/igrayscale) - コレクション内の新しい画像エフェクトのインデックス。

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

新しい Hue/Saturation/Luminance エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相を調整する角度（度）。 |
| saturation | float | 彩度を調整するパーセンテージ。 |
| luminance | float | 輝度を調整するパーセンテージ。 |

**戻り値:**
[IHSL](../../com.aspose.slides/ihsl) - コレクション内の新しい画像エフェクトのインデックス。

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

新しい Luminance エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**戻り値:**
[ILuminance](../../com.aspose.slides/iluminance) - コレクション内の新しい画像エフェクトのインデックス。

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

新しい Tint エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相をどの方向にティントするか。 |
| amount | float | 色の値がどれだけシフトするかを指定します。 |

**戻り値:**
[ITint](../../com.aspose.slides/itint) - コレクション内の新しい画像エフェクトのインデックス。

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

新しい BrightnessContrast エフェクトをコレクションの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brightness | float | 明るさを変更するパーセンテージ。 |
| contrast | float | コントラストを変更するパーセンテージ。 |

**戻り値:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - コレクション内の新しい画像エフェクトのインデックス。