---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /vi/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Cho phép tạo các thể hiện của hiệu ứng hình ảnh

--------------------

Dành cho giao diện COM.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Tạo hiệu ứng Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Tạo hiệu ứng Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Tạo hiệu ứng Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Tạo hiệu ứng Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Tạo hiệu ứng Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Tạo hiệu ứng Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Tạo hiệu ứng Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Tạo hiệu ứng BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Tạo hiệu ứng Blur. |
| [createColorChange()](#createColorChange--) | Tạo hiệu ứng Color change. |
| [createColorReplace()](#createColorReplace--) | Tạo hiệu ứng Color replace. |
| [createDuotone()](#createDuotone--) | Tạo hiệu ứng Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Tạo hiệu ứng Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Tạo hiệu ứng Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Tạo hiệu ứng Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Tạo hiệu ứng Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tạo hiệu ứng Tint. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Tạo hiệu ứng Alpha BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Threshold. |

**Giá trị trả về:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - hiệu ứng Alpha BiLevel.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Tạo hiệu ứng Alpha Ceiling.

**Giá trị trả về:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - hiệu ứng Alpha Ceiling.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Tạo hiệu ứng Alpha floor.

**Giá trị trả về:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - hiệu ứng Alpha floor.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Tạo hiệu ứng Alpha inverse.

**Giá trị trả về:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - hiệu ứng Alpha inverst.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Tạo hiệu ứng Alpha modulate.

**Giá trị trả về:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - hiệu ứng Alpha modulate.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Tạo hiệu ứng Alpha modulate fixed.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| amount | float | Amount. |

**Giá trị trả về:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - hiệu ứng Alpha modulate fixed.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Tạo hiệu ứng Alpha replace.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alpha | float | Alpha |

**Giá trị trả về:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - hiệu ứng Alpha replace.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

Tạo hiệu ứng BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Threshold. |

**Giá trị trả về:**
[IBiLevel](../../com.aspose.slides/ibilevel) - hiệu ứng BiLevel.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Tạo hiệu ứng Blur.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Giá trị trả về:**
[IBlur](../../com.aspose.slides/iblur) - hiệu ứng Blur.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Tạo hiệu ứng Color change.

**Giá trị trả về:**
[IColorChange](../../com.aspose.slides/icolorchange) - hiệu ứng Color change.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Tạo hiệu ứng Color replace.

**Giá trị trả về:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - hiệu ứng Color replace.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Tạo hiệu ứng Duotone.

**Giá trị trả về:**
[IDuotone](../../com.aspose.slides/iduotone) - hiệu ứng Duotone.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Tạo hiệu ứng Fill overlay.

**Giá trị trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - hiệu ứng Fill overlay.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Tạo hiệu ứng Gray scale.

**Giá trị trả về:**
[IGrayScale](../../com.aspose.slides/igrayscale) - hiệu ứng Gray scale.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Tạo hiệu ứng Hue Saturation Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Giá trị trả về:**
[IHSL](../../com.aspose.slides/ihsl) - hiệu ứng HSL.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Tạo hiệu ứng Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Giá trị trả về:**
[ILuminance](../../com.aspose.slides/iluminance) - hiệu ứng Luminance.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tạo hiệu ứng Tint.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Giá trị trả về:**
[ITint](../../com.aspose.slides/itint) - hiệu ứng Tint.