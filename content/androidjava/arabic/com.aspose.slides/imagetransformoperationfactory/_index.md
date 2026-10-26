---
title: ImageTransformOperationFactory
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يسمح بإنشاء عمليات تحويل الصورة
type: docs
url: /ar/com.aspose.slides/imagetransformoperationfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

يسمح بإنشاء عمليات تحويل الصورة

--------------------

لتوافق COM.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | ينشئ Alpha BiLevel effect. |
| [createAlphCeiling()](#createAlphCeiling--) | ينشئ Alpha Ceiling effect. |
| [createAlphaFloor()](#createAlphaFloor--) | ينشئ Alpha floor effect. |
| [createAlphaInverse()](#createAlphaInverse--) | ينشئ Alpha inverse effect. |
| [createAlphaModulate()](#createAlphaModulate--) | ينشئ Alpha modulate effect. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | ينشئ Alpha modulate fixed effect. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | ينشئ Alpha replace effect. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | ينشئ BiLevel effect. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | ينشئ Blur effect. |
| [createColorChange()](#createColorChange--) | ينشئ Color change effect. |
| [createColorReplace()](#createColorReplace--) | ينشئ Color replace effect. |
| [createDuotone()](#createDuotone--) | ينشئ Duotone effect. |
| [createFillOverlay()](#createFillOverlay--) | ينشئ Fill overlay effect. |
| [createGrayScale()](#createGrayScale--) | ينشئ Gray scale effect. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | ينشئ Hue Saturation Luminance effect. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | ينشئ Luminance effect. |
| [createTint(float hue, float amount)](#createTint-float-float-) | ينشئ Tint effect. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


ينشئ Alpha BiLevel effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | Threshold. |

**القيمة المرجعة:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effect.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


ينشئ Alpha Ceiling effect.

**القيمة المرجعة:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effect.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


ينشئ Alpha floor effect.

**القيمة المرجعة:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effect.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


ينشئ Alpha inverse effect.

**القيمة المرجعة:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


ينشئ Alpha modulate effect.

**القيمة المرجعة:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effect.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


ينشئ Alpha modulate fixed effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| amount | float | Amount. |

**القيمة المرجعة:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effect.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


ينشئ Alpha replace effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | float | Alpha |

**القيمة المرجعة:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effect.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


ينشئ BiLevel effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | Threshold. |

**القيمة المرجعة:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effect.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


ينشئ Blur effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**القيمة المرجعة:**
[IBlur](../../com.aspose.slides/iblur) - Blur effect.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


ينشئ Color change effect.

**القيمة المرجعة:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effect.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


ينشئ Color replace effect.

**القيمة المرجعة:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effect.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


ينشئ Duotone effect.

**القيمة المرجعة:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effect.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


ينشئ Fill overlay effect.

**القيمة المرجعة:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effect.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


ينشئ Gray scale effect.

**القيمة المرجعة:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


ينشئ Hue Saturation Luminance effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**القيمة المرجعة:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effect.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


ينشئ Luminance effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**القيمة المرجعة:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effect.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


ينشئ Tint effect.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**القيمة المرجعة:**
[ITint](../../com.aspose.slides/itint) - Tint effect.