---
title: ImageTransformOperationCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các hiệu ứng được áp dụng cho một hình ảnh.
type: docs
url: /vi/com.aspose.slides/imagetransformoperationcollection/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Biểu diễn một bộ sưu tập các hiệu ứng được áp dụng cho một hình ảnh.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Trả về một [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) từ bộ sưu tập theo chỉ mục của nó. |
| [removeAt(int index)](#removeAt-int-) | Xóa một hiệu ứng hình ảnh khỏi bộ sưu tập tại chỉ mục được chỉ định. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Thêm hiệu ứng Alpha Bi-Level mới vào cuối bộ sưu tập. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Thêm hiệu ứng Alpha Ceiling mới vào cuối bộ sưu tập. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Thêm hiệu ứng Alpha Floor mới vào cuối bộ sưu tập. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Thêm hiệu ứng Alpha Inverse mới vào cuối bộ sưu tập. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Thêm hiệu ứng Alpha Modulate mới vào cuối bộ sưu tập. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Thêm hiệu ứng Alpha Modulate Fixed mới vào cuối bộ sưu tập. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Thêm hiệu ứng Alpha Replace mới vào cuối bộ sưu tập. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Thêm hiệu ứng Bi-Level (black/white) mới vào cuối bộ sưu tập. |
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
| [size()](#size--) | Trả về số lượng hiệu ứng hình ảnh trong bộ sưu tập. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị cho biết [IGenericCollection](../../com.aspose.slides/igenericcollection) chỉ đọc hay không. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Thêm hiệu ứng hình ảnh mới vào cuối bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các hiệu ứng hình ảnh khỏi bộ sưu tập. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một mảng, bắt đầu tại một chỉ mục mảng cụ thể. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Long chỉ đọc.

**Trả về:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Trả về một [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) từ bộ sưu tập theo chỉ mục của nó.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số của phần tử. |

**Trả về:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Đối tượng [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một hiệu ứng hình ảnh khỏi bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số của một hiệu ứng hình ảnh cần xóa. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Thêm hiệu ứng Alpha Bi-Level mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Giá trị ngưỡng cho hiệu ứng alpha bi-level. |

**Trả về:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Thêm hiệu ứng Alpha Ceiling mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Thêm hiệu ứng Alpha Floor mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Thêm hiệu ứng Alpha Inverse mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Thêm hiệu ứng Alpha Modulate mới vào cuối bộ sưu tập.

**Trả về:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Thêm hiệu ứng Alpha Modulate Fixed mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| amount | float | Phần trăm để tỷ lệ alpha. |

**Trả về:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Thêm hiệu ứng Alpha Replace mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float | Giá trị độ trong suốt mới. |

**Trả về:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Thêm hiệu ứng Bi-Level (đen/trắng) mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | Ngưỡng độ sáng cho hiệu ứng Bi-Level. Các giá trị lớn hơn hoặc bằng ngưỡng sẽ được đặt thành trắng. Các giá trị nhỏ hơn ngưỡng sẽ được đặt thành đen. |

**Trả về:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Thêm hiệu ứng Blur mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| radius | double | Bán kính của hiệu ứng làm mờ. |
| grow | boolean | Xác định xem các giới hạn của đối tượng có nên mở rộng do việc làm mờ hay không. True có nghĩa là các giới hạn được mở rộng, false có nghĩa là không. |

**Trả về:**
[IBlur](../../com.aspose.slides/iblur) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Thêm hiệu ứng Color Change mới vào cuối bộ sưu tập.

**Trả về:**
[IColorChange](../../com.aspose.slides/icolorchange) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Thêm hiệu ứng Color Replacement mới vào cuối bộ sưu tập.

**Trả về:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Thêm hiệu ứng Duotone mới vào cuối bộ sưu tập.

**Trả về:**
[IDuotone](../../com.aspose.slides/iduotone) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Thêm hiệu ứng Fill Overlay mới vào cuối bộ sưu tập.

**Trả về:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Thêm hiệu ứng Gray Scale mới vào cuối bộ sưu tập.

**Trả về:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Thêm hiệu ứng Hue/Saturation/Luminance mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Số độ cần điều chỉnh hue. |
| saturation | float | Phần trăm cần điều chỉnh saturation. |
| luminance | float | Phần trăm cần điều chỉnh luminance. |

**Trả về:**
[IHSL](../../com.aspose.slides/ihsl) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Thêm hiệu ứng Luminance mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Phần trăm để thay đổi độ sáng. |
| contrast | float | Phần trăm để thay đổi độ tương phản. |

**Trả về:**
[ILuminance](../../com.aspose.slides/iluminance) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Thêm hiệu ứng Tint mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | float | Hue hướng tới mà sẽ tint. |
| amount | float | Xác định mức độ dịch chuyển giá trị màu. |

**Trả về:**
[ITint](../../com.aspose.slides/itint) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Thêm hiệu ứng BrightnessContrast mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | Phần trăm để thay đổi độ sáng. |
| contrast | float | Phần trăm để thay đổi độ tương phản. |

**Trả về:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Chỉ mục của hiệu ứng hình ảnh mới trong bộ sưu tập.

### size() {#size--}
```
public final int size()
```

Trả về số lượng hiệu ứng hình ảnh trong bộ sưu tập. int chỉ đọc.

**Trả về:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lấy giá trị cho biết [IGenericCollection](../../com.aspose.slides/igenericcollection) chỉ đọc hay không. boolean chỉ đọc.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) chỉ đọc; ngược lại, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Thêm hiệu ứng hình ảnh mới vào cuối bộ sưu tập.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Hiệu ứng hình ảnh cần thêm vào cuối bộ sưu tập. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các hiệu ứng hình ảnh khỏi bộ sưu tập.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu item được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một mảng, bắt đầu tại một chỉ mục mảng cụ thể.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Mảng một chiều là nơi nhận các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu sao chép trong mảng, tính từ 0. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Đối tượng cần xóa khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu  item  được xóa thành công khỏi [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false. Phương thức này cũng trả về false nếu item không được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection) ban đầu.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Một java.util.Iterator cho toàn bộ bộ sưu tập.