---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: اجازه می‌دهد نمونه‌های افکت‌های تصویر را ایجاد کند
type: docs
url: /fa/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

اجازه می‌دهد نمونه‌های افکت‌های تصویر را ایجاد کند

--------------------

For COM interface.
## متدها

| Method | Description |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | یک افکت Alpha BiLevel ایجاد می‌کند. |
| [createAlphCeiling()](#createAlphCeiling--) | یک افکت Alpha Ceiling ایجاد می‌کند. |
| [createAlphaFloor()](#createAlphaFloor--) | یک افکت Alpha floor ایجاد می‌کند. |
| [createAlphaInverse()](#createAlphaInverse--) | یک افکت Alpha inverse ایجاد می‌کند. |
| [createAlphaModulate()](#createAlphaModulate--) | یک افکت Alpha modulate ایجاد می‌کند. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | یک افکت Alpha modulate fixed ایجاد می‌کند. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | یک افکت Alpha replace ایجاد می‌کند. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | یک افکت BiLevel ایجاد می‌کند. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | یک افکت Blur ایجاد می‌کند. |
| [createColorChange()](#createColorChange--) | یک افکت Color change ایجاد می‌کند. |
| [createColorReplace()](#createColorReplace--) | یک افکت Color replace ایجاد می‌کند. |
| [createDuotone()](#createDuotone--) | یک افکت Duotone ایجاد می‌کند. |
| [createFillOverlay()](#createFillOverlay--) | یک افکت Fill overlay ایجاد می‌کند. |
| [createGrayScale()](#createGrayScale--) | یک افکت Gray scale ایجاد می‌کند. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | یک افکت Hue Saturation Luminance ایجاد می‌کند. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | یک افکت Luminance ایجاد می‌کند. |
| [createTint(float hue, float amount)](#createTint-float-float-) | یک افکت Tint ایجاد می‌کند. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

یک افکت Alpha BiLevel ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه. |

**بازگشت:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - افکت Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

یک افکت Alpha Ceiling ایجاد می‌کند.

**بازگشت:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - افکت Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

یک افکت Alpha floor ایجاد می‌کند.

**بازگشت:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - افکت Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

یک افکت Alpha inverse ایجاد می‌کند.

**بازگشت:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - افکت Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

یک افکت Alpha modulate ایجاد می‌کند.

**بازگشت:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - افکت Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

یک افکت Alpha modulate fixed ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| amount | float | مقدار. |

**بازگشت:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - افکت Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

یک افکت Alpha replace ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alpha | float | Alpha |

**بازگشت:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - افکت Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

یک افکت BiLevel ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه. |

**بازگشت:**
[IBiLevel](../../com.aspose.slides/ibilevel) - افکت BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

یک افکت Blur ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع. |
| grow | boolean | رشد. |

**بازگشت:**
[IBlur](../../com.aspose.slides/iblur) - افکت Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

یک افکت Color change ایجاد می‌کند.

**بازگشت:**
[IColorChange](../../com.aspose.slides/icolorchange) - افکت Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

یک افکت Color replace ایجاد می‌کند.

**بازگشت:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - افکت Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

یک افکت Duotone ایجاد می‌کند.

**بازگشت:**
[IDuotone](../../com.aspose.slides/iduotone) - افکت Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

یک افکت Fill overlay ایجاد می‌کند.

**بازگشت:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - افکت Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

یک افکت Gray scale ایجاد می‌کند.

**بازگشت:**
[IGrayScale](../../com.aspose.slides/igrayscale) - افکت Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

یک افکت Hue Saturation Luminance ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**بازگشت:**
[IHSL](../../com.aspose.slides/ihsl) - افکت HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

یک افکت Luminance ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | روشنایی. |
| contrast | float | کنتراست. |

**بازگشت:**
[ILuminance](../../com.aspose.slides/iluminance) - افکت Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

یک افکت Tint ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | مقدار. |

**بازگشت:**
[ITint](../../com.aspose.slides/itint) - افکت Tint.