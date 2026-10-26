---
title: ImageTransformOperationFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo các thao tác biến đổi hình ảnh
type: docs
url: /vi/com.aspose.slides/imagetransformoperationfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Cho phép tạo các thao tác biến đổi hình ảnh

--------------------

Để tương thích COM.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Tạo hiệu Alpha BiLevel. |
| [createAlphCeiling()](#createAlphCeiling--) | Tạo hiệu Alpha Ceiling. |
| [createAlphaFloor()](#createAlphaFloor--) | Tạo hiệu Alpha floor. |
| [createAlphaInverse()](#createAlphaInverse--) | Tạo hiệu Alpha inverse. |
| [createAlphaModulate()](#createAlphaModulate--) | Tạo hiệu Alpha modulate. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Tạo hiệu Alpha modulate fixed. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Tạo hiệu Alpha replace. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Tạo hiệu BiLevel. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Tạo hiệu Blur. |
| [createColorChange()](#createColorChange--) | Tạo hiệu Color change. |
| [createColorReplace()](#createColorReplace--) | Tạo hiệu Color replace. |
| [createDuotone()](#createDuotone--) | Tạo hiệu Duotone. |
| [createFillOverlay()](#createFillOverlay--) | Tạo hiệu Fill overlay. |
| [createGrayScale()](#createGrayScale--) | Tạo hiệu Gray scale. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Tạo hiệu Hue Saturation Luminance. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Tạo hiệu Luminance. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tạo hiệu Tint. |

### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```

### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Tạo hiệu Alpha BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Ngưỡng. |

**Trả về:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - hiệu Alpha BiLevel.

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```

Tạo hiệu Alpha Ceiling.

**Trả về:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - hiệu Alpha Ceiling.

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```

Tạo hiệu Alpha floor.

**Trả về:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - hiệu Alpha floor.

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```

Tạo hiệu Alpha inverse.

**Trả về:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - hiệu Alpha inverst.

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```

Tạo hiệu Alpha modulate.

**Trả về:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - hiệu Alpha modulate.

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Tạo hiệu Alpha modulate fixed.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| amount | float | Số lượng. |

**Trả về:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - hiệu Alpha modulate fixed.

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```

Tạo hiệu Alpha replace.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alpha | float | Alpha |

**Trả về:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - hiệu Alpha replace.

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```

Tạo hiệu BiLevel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Ngưỡng. |

**Trả về:**
[IBiLevel](../../com.aspose.slides/ibilevel) - hiệu BiLevel.

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```

Tạo hiệu Blur.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Bán kính. |
| grow | boolean | Mở rộng. |

**Trả về:**
[IBlur](../../com.aspose.slides/iblur) - hiệu Blur.

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```

Tạo hiệu Color change.

**Trả về:**
[IColorChange](../../com.aspose.slides/icolorchange) - hiệu Color change.

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```

Tạo hiệu Color replace.

**Trả về:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - hiệu Color replace.

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```

Tạo hiệu Duotone.

**Trả về:**
[IDuotone](../../com.aspose.slides/iduotone) - hiệu Duotone.

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```

Tạo hiệu Fill overlay.

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - hiệu Fill overlay.

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```

Tạo hiệu Gray scale.

**Trả về:**
[IGrayScale](../../com.aspose.slides/igrayscale) - trả về hiệu Gray scale.

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```

Tạo hiệu Hue Saturation Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Màu sắc. |
| saturation | float | Độ bão hòa. |
| luminance | float | Độ sáng. |

**Trả về:**
[IHSL](../../com.aspose.slides/ihsl) - hiệu HSL.

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```

Tạo hiệu Luminance.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| brightness | float | Độ sáng. |
| contrast | float | Độ tương phản. |

**Trả về:**
[ILuminance](../../com.aspose.slides/iluminance) - hiệu Luminance.

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```

Tạo hiệu Tint.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Màu sắc. |
| amount | float | Số lượng. |

**Trả về:**
[ITint](../../com.aspose.slides/itint) - hiệu Tint.