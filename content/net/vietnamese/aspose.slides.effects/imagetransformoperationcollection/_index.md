---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes cho .NET Tham khảo API
description: Đại diện cho một bộ sưu tập các hiệu ứng được áp dụng cho một hình ảnh.
type: docs
weight: 3580
url: /vi/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection lớp

Đại diện cho một bộ sưu tập các hiệu ứng được áp dụng cho một hình ảnh.

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | Trả về số lượng hiệu ứng ảnh trong bộ sưu tập. Chỉ đọc Int32. |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | Lấy giá trị cho biết ICollection có phải chỉ đọc hay không. Chỉ đọc Boolean. |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | Trả về một [`ImageTransformOperation`](../imagetransformoperation) từ bộ sưu tập theo chỉ số của nó. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | Thêm hiệu ứng ảnh mới vào cuối bộ sưu tập. |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | Thêm hiệu ứng Alpha Bi-Level mới vào cuối bộ sưu tập. |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | Thêm hiệu ứng Alpha Ceiling mới vào cuối bộ sưu tập. |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | Thêm hiệu ứng Alpha Floor mới vào cuối bộ sưu tập. |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | Thêm hiệu ứng Alpha Inverse mới vào cuối bộ sưu tập. |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | Thêm hiệu ứng Alpha Modulate mới vào cuối bộ sưu tập. |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | Thêm hiệu ứng Alpha Modulate Fixed mới vào cuối bộ sưu tập. |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | Thêm hiệu ứng Alpha Replace mới vào cuối bộ sưu tập. |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | Thêm hiệu ứng Bi-Level (đen/trắng) mới vào cuối bộ sưu tập. |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | Thêm hiệu ứng Blur mới vào cuối bộ sưu tập. |
| [AddBrightnessContrastEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbrightnesscontrasteffect)(float, float) | Thêm hiệu ứng BrightnessContrast mới vào cuối bộ sưu tập. |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | Thêm hiệu ứng Color Change mới vào cuối bộ sưu tập. |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | Thêm hiệu ứng Color Replacement mới vào cuối bộ sưu tập. |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | Thêm hiệu ứng Duotone mới vào cuối bộ sưu tập. |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | Thêm hiệu ứng Fill Overlay mới vào cuối bộ sưu tập. |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | Thêm hiệu ứng Gray Scale mới vào cuối bộ sưu tập. |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | Thêm hiệu ứng Hue/Saturation/Luminance mới vào cuối bộ sưu tập. |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | Thêm hiệu ứng Luminance mới vào cuối bộ sưu tập. |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | Thêm hiệu ứng Tint mới vào cuối bộ sưu tập. |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | Xóa toàn bộ hiệu ứng ảnh khỏi bộ sưu tập. |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | Xác định liệu ICollection có chứa giá trị cụ thể hay không. |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | Sao chép các phần tử của ICollection vào một Array, bắt đầu tại một chỉ số Array nhất định. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | So sánh với đối tượng được chỉ định. |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | Trả về một enumerator để duyệt qua bộ sưu tập. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Trả về mã băm. |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi ICollection. |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | Xóa một hiệu ứng ảnh khỏi bộ sưu tập tại chỉ số được chỉ định. |

### Xem thêm

* lớp [PVIObject](../../aspose.slides/pviobject)
* giao diện [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* không gian tên [Aspose.Slides.Effects](../../aspose.slides.effects)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->