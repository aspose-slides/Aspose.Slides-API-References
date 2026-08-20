---
title: IImageTransformOperationFactory
second_title: Aspose.Slides لـ Java مرجع API
description: يسمح بإنشاء مثيلات تأثيرات الصورة
type: docs
url: /ar/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

يسمح بإنشاء مثيلات تأثيرات الصورة

--------------------

لواجهة COM.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | ينشئ تأثير Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | ينشئ تأثير Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | ينشئ تأثير Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | ينشئ تأثير Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | ينشئ تأثير Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | ينشئ تأثير Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | ينشئ تأثير Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | ينشئ تأثير BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | ينشئ تأثير Blur. |
| [createColorChange()](#createColorChange--) | ينشئ تأثير Color change. |
| [createColorReplace()](#createColorReplace--) | ينشئ تأثير Color replace. |
| [createDuotone()](#createDuotone--) | ينشئ تأثير Duotone. |
| [createFillOverlay()](#createFillOverlay--) | ينشئ تأثير Fill overlay. |
| [createGrayScale()](#createGrayScale--) | ينشئ تأثير Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | ينشئ تأثير Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | ينشئ تأثير Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | ينشئ تأثير Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

ينشئ تأثير Alpha BiLevel.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| threshold | float | Threshold. |

**القيمة المرجعة:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - تأثير Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

ينشئ تأثير Alpha Ceiling.

**القيمة المرجعة:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - تأثير Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

ينشئ تأثير Alpha floor.

**القيمة المرجعة:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - تأثير Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

ينشئ تأثير Alpha inverse.

**القيمة المرجعة:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - تأثير Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

ينشئ تأثير Alpha modulate.

**القيمة المرجعة:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - تأثير Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

ينشئ تأثير Alpha modulate fixed.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| amount | float | Amount. |

**القيمة المرجعة:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - تأثير Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

ينشئ تأثير Alpha replace.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| alpha | float | Alpha |

**القيمة المرجعة:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - تأثير Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

ينشئ تأثير BiLevel.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| threshold | float | Threshold. |

**القيمة المرجعة:**
[IBiLevel](../../com.aspose.slides/ibilevel) - تأثير BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

ينشئ تأثير Blur.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**القيمة المرجعة:**
[IBlur](../../com.aspose.slides/iblur) - تأثير Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

ينشئ تأثير Color change.

**القيمة المرجعة:**
[IColorChange](../../com.aspose.slides/icolorchange) - تأثير Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

ينشئ تأثير Color replace.

**القيمة المرجعة:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - تأثير Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

ينشئ تأثير Duotone.

**القيمة المرجعة:**
[IDuotone](../../com.aspose.slides/iduotone) - تأثير Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

ينشئ تأثير Fill overlay.

**القيمة المرجعة:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - تأثير Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

ينشئ تأثير Gray scale.

**القيمة المرجعة:**
[IGrayScale](../../com.aspose.slides/igrayscale) - تأثير Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

ينشئ تأثير Hue Saturation Luminance.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**القيمة المرجعة:**
[IHSL](../../com.aspose.slides/ihsl) - تأثير HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

ينشئ تأثير Luminance.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**القيمة المرجعة:**
[ILuminance](../../com.aspose.slides/iluminance) - تأثير Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

ينشئ تأثير Tint.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**القيمة المرجعة:**
[ITint](../../com.aspose.slides/itint) - تأثير Tint.