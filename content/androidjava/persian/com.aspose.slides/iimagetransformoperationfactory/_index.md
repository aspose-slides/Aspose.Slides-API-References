---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /fa/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

به شما امکان می‌دهد نمونه‌های اثرهای تصویر را ایجاد کنید

--------------------

برای رابط COM.
## متدها

| متد | توضیح |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | اثر Alpha BiLevel را ایجاد می‌کند. |
| [createAlphCeiling()](#createAlphCeiling--) | اثر Alpha Ceiling را ایجاد می‌کند. |
| [createAlphaFloor()](#createAlphaFloor--) | اثر Alpha floor را ایجاد می‌کند. |
| [createAlphaInverse()](#createAlphaInverse--) | اثر Alpha inverse را ایجاد می‌کند. |
| [createAlphaModulate()](#createAlphaModulate--) | اثر Alpha modulate را ایجاد می‌کند. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | اثر Alpha modulate fixed را ایجاد می‌کند. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | اثر Alpha replace را ایجاد می‌کند. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | اثر BiLevel را ایجاد می‌کند. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | اثر Blur را ایجاد می‌کند. |
| [createColorChange()](#createColorChange--) | اثر Color change را ایجاد می‌کند. |
| [createColorReplace()](#createColorReplace--) | اثر Color replace را ایجاد می‌کند. |
| [createDuotone()](#createDuotone--) | اثر Duotone را ایجاد می‌کند. |
| [createFillOverlay()](#createFillOverlay--) | اثر Fill overlay را ایجاد می‌کند. |
| [createGrayScale()](#createGrayScale--) | اثر Gray scale را ایجاد می‌کند. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | اثر Hue Saturation Luminance را ایجاد می‌کند. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | اثر Luminance را ایجاد می‌کند. |
| [createTint(float hue, float amount)](#createTint-float-float-) | اثر Tint را ایجاد می‌کند. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

اثر Alpha BiLevel را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه. |

**بازگشت:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - اثر Alpha BiLevel
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

اثر Alpha Ceiling را ایجاد می‌کند.

**بازگشت:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - اثر Alpha Ceiling
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

اثر Alpha floor را ایجاد می‌کند.

**بازگشت:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - اثر Alpha floor
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

اثر Alpha inverse را ایجاد می‌کند.

**بازگشت:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - اثر Alpha inverse
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

اثر Alpha modulate را ایجاد می‌کند.

**بازگشت:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - اثر Alpha modulate
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

اثر Alpha modulate fixed را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| amount | float | مقدار. |

**بازگشت:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - اثر Alpha modulate fixed
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

اثر Alpha replace را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alpha | float | Alpha |

**بازگشت:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - اثر Alpha replace
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

اثر BiLevel را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه. |

**بازگشت:**
[IBiLevel](../../com.aspose.slides/ibilevel) - اثر BiLevel
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

اثر Blur را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع. |
| grow | boolean | رشد. |

**بازگشت:**
[IBlur](../../com.aspose.slides/iblur) - اثر Blur
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

اثر Color change را ایجاد می‌کند.

**بازگشت:**
[IColorChange](../../com.aspose.slides/icolorchange) - اثر Color change
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

اثر Color replace را ایجاد می‌کند.

**بازگشت:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - اثر Color replace
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

اثر Duotone را ایجاد می‌کند.

**بازگشت:**
[IDuotone](../../com.aspose.slides/iduotone) - اثر Duotone
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

اثر Fill overlay را ایجاد می‌کند.

**بازگشت:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - اثر Fill overlay
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

اثر Gray scale را ایجاد می‌کند.

**بازگشت:**
[IGrayScale](../../com.aspose.slides/igrayscale) - اثر Gray scale
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

اثر Hue Saturation Luminance را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**بازگشت:**
[IHSL](../../com.aspose.slides/ihsl) - اثر HSL
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

اثر Luminance را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | روشنایی. |
| contrast | float | کنتراست. |

**بازگشت:**
[ILuminance](../../com.aspose.slides/iluminance) - اثر Luminance
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

اثر Tint را ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**بازگشت:**
[ITint](../../com.aspose.slides/itint) - اثر Tint