---
title: ImageTransformOperationFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo các thao tác biến đổi hình ảnh
type: docs
url: /vi/com.aspose.slides/imagetransformoperationfactory/
---
**Kế thừa:**  
java.lang.Object

**Tất cả giao diện được thực thi:**  
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)  
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Cho phép tạo các hoạt động biến đổi hình ảnh

--------------------

Để tương thích với COM.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
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
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Tạo hiệu ứng Alpha BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Ngưỡng. |

**Trả về:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - hiệu ứng Alpha BiLevel.

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Tạo hiệu ứng Alpha Ceiling.

**Trả về:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - hiệu ứng Alpha Ceiling.

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Tạo hiệu ứng Alpha floor.

**Trả về:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - hiệu ứng Alpha floor.

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Tạo hiệu ứng Alpha inverse.

**Trả về:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - hiệu ứng Alpha inverst.

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Tạo hiệu ứng Alpha modulate.

**Trả về:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - hiệu ứng Alpha modulate.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Tạo hiệu ứng Alpha modulate fixed.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| amount | float | Số lượng. |

**Trả về:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - hiệu ứng Alpha modulate fixed.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Tạo hiệu ứng Alpha replace.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alpha | float | Alpha |

**Trả về:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - hiệu ứng Alpha replace.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Tạo hiệu ứng BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Ngưỡng. |

**Trả về:**
[IBiLevel](../../com.aspose.slides/ibilevel) - hiệu ứng BiLevel.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Tạo hiệu ứng Blur.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Bán kính. |
| grow | boolean | Grow. |

**Trả về:**
[IBlur](../../com.aspose.slides/iblur) - hiệu ứng Blur.

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Tạo hiệu ứng Color change.

**Trả về:**
[IColorChange](../../com.aspose.slides/icolorchange) - hiệu ứng Color change.

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Tạo hiệu ứng Color replace.

**Trả về:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - hiệu ứng Color replace.

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Tạo hiệu ứng Duotone.

**Trả về:**
[IDuotone](../../com.aspose.slides/iduotone) - hiệu ứng Duotone.

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Tạo hiệu ứng Fill overlay.

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - hiệu ứng Fill overlay.

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Tạo hiệu ứng Gray scale.

**Trả về:**
[IGrayScale](../../com.aspose.slides/igrayscale) - hiệu ứng Gray scale.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Tạo hiệu ứng Hue Saturation Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Trả về:**
[IHSL](../../com.aspose.slides/ihsl) - hiệu ứng HSL.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Tạo hiệu ứng Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Trả về:**
[ILuminance](../../com.aspose.slides/iluminance) - hiệu ứng Luminance.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Tạo hiệu ứng Tint.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Trả về:**
[ITint](../../com.aspose.slides/itint) - hiệu ứng Tint.