---
title: TiffOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn kiểm soát cách một bài thuyết trình được lưu dưới định dạng TIFF.
type: docs
weight: 4570
url: /vi/aspose.slides.export/tiffoptions/
---
## TiffOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bài thuyết trình được lưu dưới định dạng TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [TiffOptions](tiffoptions)() | Hàm khởi tạo mặc định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Xác định thuật toán chuyển đổi ảnh màu thành ảnh đen trắng. Tùy chọn này sẽ được áp dụng chỉ nếu [`CompressionType`](./compressiontype) được đặt thành CCITT4 hoặc CCITT3 Đọc/ghi [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Mặc định là Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Xác định kiểu nén. Đọc/ghi [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc thiết lập phông chữ được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Xác định độ phân giải ngang tính bằng điểm/inch. Đọc/ghi UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Xác định độ phân giải dọc tính bằng điểm/inch. Đọc/ghi UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc thiết lập kiểu hiển thị của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Xác định kích thước của ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước ảnh được tạo sẽ được tính dựa trên giá trị kích thước slide của bài thuyết trình. Đọc/ghi Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Xác định định dạng pixel cho các ảnh được tạo. Đọc/ghi [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Xác định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Xác định có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bài thuyết trình hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Lấy hoặc thiết lập chế độ sắp xếp slide trên trang khi xuất một bài thuyết trình [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang TIFF với kích thước mặc định.

```csharp
[C#]
// Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Lưu trình chiếu thành tài liệu TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang TIFF với kích thước tùy chỉnh.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho một tệp Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Khởi tạo lớp TiffOptions
    TiffOptions opts = new TiffOptions();
    // Thiết lập kiểu nén
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Các loại nén
    // Mặc định - Xác định sơ đồ nén mặc định (LZW).
    // Không - Xác định không có nén.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Độ sâu phụ thuộc vào kiểu nén và không thể thiết lập thủ công.
    // Đơn vị độ phân giải luôn bằng “2” (điểm trên mỗi inch)
    // Thiết lập DPI của ảnh
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Thiết lập kích thước ảnh
    opts.ImageSize = new Size(1728, 1078);
    // Lưu trình chiếu thành TIFF với kích thước ảnh đã chỉ định
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Ví dụ sau đây cho thấy cách chuyển đổi PowerPoint sang TIFF với định dạng pixel ảnh tùy chỉnh.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho một tệp Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat chứa các giá trị sau (như có thể thấy trong tài liệu):
    Format1bppIndexed; // 1 bit trên mỗi pixel, dạng chỉ mục.
    Format4bppIndexed; // 4 bit trên mỗi pixel, dạng chỉ mục.
    Format8bppIndexed; // 8 bit trên mỗi pixel, dạng chỉ mục.
    Format24bppRgb; // 24 bit trên mỗi pixel, RGB.
    Format32bppArgb; // 32 bit trên mỗi pixel, ARGB.
    */
    // Lưu trình chiếu thành TIFF với kích thước ảnh đã chỉ định
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [ITiffOptions](../itiffoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* bộ chứa [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->