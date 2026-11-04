---
title: IPictureFillFormat
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Đại diện cho kiểu lấp đầy ảnh.
type: docs
weight: 6670
url: /vi/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat giao diện

Represents a picture fill style.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Cho phép lấy giao diện IFillParamSource cơ bản. Read-only [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt bỏ ở phía dưới của ảnh. Read/write Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt bỏ ở phía bên trái của ảnh. Read/write Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Trả về hoặc đặt số phần trăm chiều rộng thực của hình ảnh bị cắt bỏ ở phía bên phải của ảnh. Read/write Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Trả về hoặc đặt số phần trăm chiều cao thực của hình ảnh bị cắt bỏ ở phía trên của ảnh. Read/write Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Trả về hoặc đặt dpi được sử dụng để lấp đầy ảnh. Read/write Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Trả về ảnh. Read-only [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Trả về hoặc đặt chế độ lấp đầy ảnh. Read/write [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Trả về hoặc đặt cạnh dưới của hình chữ nhật lấp đầy được xác định bởi độ lệch phần trăm từ cạnh dưới của hộp bao của hình dạng. Giá trị phần trăm dương chỉ ra nội lệch, trong khi giá trị âm chỉ ra ngoại lệch. Read/write Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Trả về hoặc đặt cạnh trái của hình chữ nhật lấp đầy được xác định bởi độ lệch phần trăm từ cạnh trái của hộp bao của hình dạng. Giá trị phần trăm dương chỉ ra nội lệch, trong khi giá trị âm chỉ ra ngoại lệch. Read/write Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Trả về hoặc đặt cạnh phải của hình chữ nhật lấp đầy được xác định bởi độ lệch phần trăm từ cạnh phải của hộp bao của hình dạng. Giá trị phần trăm dương chỉ ra nội lệch, trong khi giá trị âm chỉ ra ngoại lệch. Read/write Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Trả về hoặc đặt cạnh trên của hình chữ nhật lấp đầy được xác định bởi độ lệch phần trăm từ cạnh trên của hộp bao của hình dạng. Giá trị phần trăm dương chỉ ra nội lệch, trong khi giá trị âm chỉ ra ngoại lệch. Read/write Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Trả về hoặc đặt cách mà texture được căn chỉnh trong hình dạng. Cài đặt này kiểm soát điểm bắt đầu của mẫu texture và cách nó lặp lại trên hình dạng. Read/write [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Lật ô texture quanh trục ngang, dọc hoặc cả hai trục. Read/write [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Trả về hoặc đặt độ lệch ngang của texture từ gốc của hình dạng tính bằng điểm. Giá trị dương di chuyển texture sang phải, trong khi giá trị âm di chuyển sang trái. Read/write Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Trả về hoặc đặt độ lệch dọc của texture từ gốc của hình dạng tính bằng điểm. Giá trị dương di chuyển texture xuống, trong khi giá trị âm di chuyển lên. Read/write Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Trả về hoặc đặt tỉ lệ ngang cho texture fill dưới dạng phần trăm. Read/write Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Trả về hoặc đặt tỉ lệ dọc cho texture fill dưới dạng phần trăm. Read/write Single. |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng xóa các vùng đã cắt. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Nén ảnh bằng cách giảm kích thước dựa trên kích thước hình dạng và độ phân giải đã chỉ định. Tùy chọn, nó cũng xóa các vùng đã cắt. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Xóa các vùng đã cắt của Picture lấp đầy. |

### Xem thêm

* giao diện [IFillParamSource](../ifillparamsource)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->