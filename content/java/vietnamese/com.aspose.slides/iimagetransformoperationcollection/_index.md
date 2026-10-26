---
title: IImageTransformOperationCollection
second_title: Tài liệu tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các hiệu ứng được áp dụng cho hình ảnh.
type: docs
url: /vi/com.aspose.slides/iimagetransformoperationcollection/
---
**Tất cả giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Biểu diễn một bộ sưu tập các hiệu ứng được áp dụng cho hình ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về một [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) từ bộ sưu tập theo chỉ mục của nó. |
| [removeAt(int index)](#removeAt-int-) | Xóa một hiệu ứng hình ảnh khỏi bộ sưu tập tại chỉ mục được chỉ định. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Thêm hiệu ứng Alpha Bi-Level mới vào cuối bộ sưu tập. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Thêm hiệu ứng Alpha Ceiling mới vào cuối bộ sưu tập. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Thêm hiệu ứng Alpha Floor mới vào cuối bộ sưu tập. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Thêm hiệu ứng Alpha Inverse mới vào cuối bộ sưu tập. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Thêm hiệu ứng Alpha Modulate mới vào cuối bộ sưu tập. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Thêm hiệu ứng Alpha Modulate Fixed mới vào cuối bộ sưu tập. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Thêm hiệu ứng Alpha Replace mới vào cuối bộ sưu tập. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Thêm hiệu ứng Bi-Level (đen/trắng) mới vào cuối bộ sưu tập. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Thêm hiệu ứng Blur mới vào cuối bộ sưu tập. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Thêm hiệu ứng Color Change mới vào cuối bộ sưu tập. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Thêm hiệu ứng Color Replacement mới vào cuối bộ sưu tập. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Thêm hiệu ứng Duotone mới vào cuối bộ sưu tập. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Thêm hiệu ứng Fill Overlay mới vào cuối bộ sưu tập. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Thêm hiệu ứng Gray Scale mới vào cuối bộ sưu tập. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Thêm hiệu ứng Hue/Saturation/Luminance mới vào cuối bộ sưu tập. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Thêm hiệu ứng Luminance mới vào cuối bộ sưu tập. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Thêm hiệu ứng Tint mới vào cuối bộ sưu tập. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Thêm hiệu ứng BrightnessContrast mới vào cuối bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Trả về một [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) từ bộ sưu tập theo chỉ mục của nó.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của mục. |

**Trả về:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Đối tượng [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một hiệu ứng hình ảnh khỏi bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hiệu ứng hình ảnh cần xóa. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Thêm hiệu ứng Alpha Bi-Level mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | Giá trị ngưỡng cho hiệu ứng alpha bi-level. |

**Trả về:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Thêm hiệu ứng Alpha Ceiling mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Thêm hiệu ứng Alpha Floor mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Thêm hiệu ứng Alpha Inverse mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Thêm hiệu ứng Alpha Modulate mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Thêm hiệu ứng Alpha Modulate Fixed mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| amount | float | Phần trăm để điều chỉnh alpha. |

**Trả về:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Thêm hiệu ứng Alpha Replace mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| alpha | float | Giá trị độ mờ mới. |

**Trả về:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Thêm hiệu ứng Bi-Level (đen/trắng) mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| threshold | float | ngưỡng độ sáng cho hiệu ứng Bi-Level. Các giá trị lớn hơn hoặc bằng ngưỡng sẽ được đặt thành màu trắng. Các giá trị nhỏ hơn ngưỡng sẽ được đặt thành màu đen. |

**Trả về:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Thêm hiệu ứng Blur mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| radius | double | Bán kính của hiệu ứng làm mờ. |
| grow | boolean | Chỉ định liệu các giới hạn của đối tượng có nên mở rộng do hiệu ứng làm mờ hay không. True cho biết các giới hạn được mở rộng, trong khi false cho biết không được mở rộng. |

**Trả về:**
[IBlur](../../com.aspose.slides/iblur) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Thêm hiệu ứng Color Change mới vào cuối bộ sưu tập.

**Trả về:**
[IColorChange](../../com.aspose.slides/icolorchange) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Thêm hiệu ứng Color Replacement mới vào cuối bộ sưu tập.

**Trả về:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Thêm hiệu ứng Duotone mới vào cuối bộ sưu tập.

**Trả về:**
[IDuotone](../../com.aspose.slides/iduotone) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Thêm hiệu ứng Fill Overlay mới vào cuối bộ sưu tập.

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Thêm hiệu ứng Gray Scale mới vào cuối bộ sưu tập.

**Trả về:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Thêm hiệu ứng Hue/Saturation/Luminance mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Số độ mà màu sắc được điều chỉnh. |
| saturation | float | Phần trăm mà độ bão hòa được điều chỉnh. |
| luminance | float | Phần trăm mà độ sáng được điều chỉnh. |

**Trả về:**
[IHSL](../../com.aspose.slides/ihsl) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Thêm hiệu ứng Luminance mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| brightness | float | Phần trăm để thay đổi độ sáng. |
| contrast | float | Phần trăm để thay đổi độ tương phản. |

**Trả về:**
[ILuminance](../../com.aspose.slides/iluminance) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Thêm hiệu ứng Tint mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hue | float | Màu sắc cần tint. |
| amount | float | Xác định mức độ dịch chuyển giá trị màu. |

**Trả về:**
[ITint](../../com.aspose.slides/itint) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Thêm hiệu ứng BrightnessContrast mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| brightness | float | Phần trăm để thay đổi độ sáng. |
| contrast | float | Phần trăm để thay đổi độ tương phản. |

**Trả về:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.