---
title: IPictureFillFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu thị kiểu tô đầy bằng hình ảnh.
type: docs
weight: 6650
url: /vi/aspose.slides/ipicturefillformat/
---
## Giao diện IPictureFillFormat

Biểu thị kiểu tô đầy bằng hình ảnh.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Cho phép lấy giao diện IFillParamSource cơ bản. Chỉ đọc [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt bỏ ở đáy của ảnh. Đọc/ghi Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt bỏ ở phía trái của ảnh. Đọc/ghi Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt bỏ ở phía phải của ảnh. Đọc/ghi Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt bỏ ở phía trên của ảnh. Đọc/ghi Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Trả về hoặc đặt dpi được sử dụng để tô đầy hình ảnh. Đọc/ghi Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Trả về hình ảnh. Chỉ đọc [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Trả về hoặc đặt chế độ tô đầy hình ảnh. Đọc/ghi [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Trả về hoặc đặt cạnh dưới của hình chữ nhật tô đầy được xác định bằng khoảng lệch phần trăm từ cạnh dưới của hộp bao quanh hình dạng. Giá trị phần trăm dương chỉ vị trí lùi vào, trong khi phần trăm âm chỉ vị trí lệch ra bên ngoài. Đọc/ghi Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Trả về hoặc đặt cạnh trái của hình chữ nhật tô đầy được xác định bằng khoảng lệch phần trăm từ cạnh trái của hộp bao quanh hình dạng. Giá trị phần trăm dương chỉ vị trí lùi vào, trong khi phần trăm âm chỉ vị trí lệch ra bên ngoài. Đọc/ghi Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Trả về hoặc đặt cạnh phải của hình chữ nhật tô đầy được xác định bằng khoảng lệch phần trăm từ cạnh phải của hộp bao quanh hình dạng. Giá trị phần trăm dương chỉ vị trí lùi vào, trong khi phần trăm âm chỉ vị trí lệch ra bên ngoài. Đọc/ghi Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Trả về hoặc đặt cạnh trên của hình chữ nhật tô đầy được xác định bằng khoảng lệch phần trăm từ cạnh trên của hộp bao quanh hình dạng. Giá trị phần trăm dương chỉ vị trí lùi vào, trong khi phần trăm âm chỉ vị trí lệch ra bên ngoài. Đọc/ghi Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Trả về hoặc đặt cách căn chỉnh kết cấu bên trong hình dạng. Cài đặt này kiểm soát điểm bắt đầu của mẫu kết cấu và cách nó lặp lại trên hình dạng. Đọc/ghi [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Lật ô kết cấu quanh trục ngang, dọc hoặc cả hai. Đọc/ghi [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Trả về hoặc đặt độ lệch ngang của kết cấu so với gốc của hình dạng tính bằng điểm. Giá trị dương di chuyển kết cấu sang phải, trong khi giá trị âm di chuyển sang trái. Đọc/ghi Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Trả về hoặc đặt độ lệch dọc của kết cấu so với gốc của hình dạng tính bằng điểm. Giá trị dương di chuyển kết cấu xuống, trong khi giá trị âm di chuyển lên trên. Đọc/ghi Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Trả về hoặc đặt tỷ lệ ngang cho việc tô kết cấu dưới dạng phần trăm. Đọc/ghi Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Trả về hoặc đặt tỷ lệ dọc cho việc tô kết cấu dưới dạng phần trăm. Đọc/ghi Single. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng sẽ xóa các vùng đã cắt. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Nén hình ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng sẽ xóa các vùng đã cắt. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Xóa các vùng đã cắt của hình ảnh được tô đầy. |

### Xem thêm

* giao diện [IFillParamSource](../ifillparamsource)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->