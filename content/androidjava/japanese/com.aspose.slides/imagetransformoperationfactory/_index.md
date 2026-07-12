---
title: ImageTransformOperationFactory
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: 画像変換操作を作成できます
type: docs
url: /ja/com.aspose.slides/imagetransformoperationfactory/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)  
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

画像変換操作を作成できます

--------------------

COM 互換性のためです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel エフェクトを作成します。 |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling エフェクトを作成します。 |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor エフェクトを作成します。 |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse エフェクトを作成します。 |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate エフェクトを作成します。 |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed エフェクトを作成します。 |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace エフェクトを作成します。 |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel エフェクトを作成します。 |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur エフェクトを作成します。 |
| [createColorChange()](#createColorChange--) | Color change エフェクトを作成します。 |
| [createColorReplace()](#createColorReplace--) | Color replace エフェクトを作成します。 |
| [createDuotone()](#createDuotone--) | Duotone エフェクトを作成します。 |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay エフェクトを作成します。 |
| [createGrayScale()](#createGrayScale--) | Gray scale エフェクトを作成します。 |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance エフェクトを作成します。 |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance エフェクトを作成します。 |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint エフェクトを作成します。 |

### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | 閾値。 |

**戻り値:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel エフェクト。

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling エフェクトを作成します。

**戻り値:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling エフェクト。

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Alpha floor エフェクトを作成します。

**戻り値:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor エフェクト。

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Alpha inverse エフェクトを作成します。

**戻り値:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverse エフェクト。

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Alpha modulate エフェクトを作成します。

**戻り値:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate エフェクト。

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| amount | float | 量。 |

**戻り値:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed エフェクト。

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alpha | float | Alpha |

**戻り値:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace エフェクト。

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

BiLevel エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threshold | float | 閾値。 |

**戻り値:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel エフェクト。

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Blur エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 拡大。 |

**戻り値:**
[IBlur](../../com.aspose.slides/iblur) - Blur エフェクト。

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Color change エフェクトを作成します。

**戻り値:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change エフェクト。

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Color replace エフェクトを作成します。

**戻り値:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace エフェクト。

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Duotone エフェクトを作成します。

**戻り値:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone エフェクト。

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Fill overlay エフェクトを作成します。

**戻り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay エフェクト。

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Gray scale エフェクトを作成します。

**戻り値:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale エフェクト。

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相。 |
| saturation | float | 彩度。 |
| luminance | float | 輝度。 |

**戻り値:**
[IHSL](../../com.aspose.slides/ihsl) - HSL エフェクト。

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Luminance エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brightness | float | 明るさ。 |
| contrast | float | コントラスト。 |

**戻り値:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance エフェクト。

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Tint エフェクトを作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hue | float | 色相。 |
| amount | float | 量。 |

**戻り値:**
[ITint](../../com.aspose.slides/itint) - Tint エフェクト。