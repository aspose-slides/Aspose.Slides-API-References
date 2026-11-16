---
title: TiffOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới định dạng TIFF.
type: docs
weight: 4590
url: /vi/aspose.slides.export/tiffoptions/
---
## Lớp TiffOptions

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới định dạng TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Hàm khởi tạo

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Default constructor. |

## Thuộc tính

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. Tùy chọn này sẽ chỉ được áp dụng nếu [`CompressionType`](./compressiontype) được đặt thành CCITT4 hoặc CCITT3 Đọc/ghi [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Mặc định là Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Xác định loại nén. Đọc/ghi [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Xác định độ phân giải ngang tính bằng điểm trên inch. Đọc/ghi UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Xác định độ phân giải dọc tính bằng điểm trên inch. Đọc/ghi UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu hiển thị của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Xác định kích thước của ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước ảnh được tạo sẽ được tính dựa trên giá trị kích thước slide của bản trình bày. Đọc/ghi Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Xác định định dạng pixel cho các ảnh được tạo. Đọc/ghi [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Xác định có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ mà các slide được bố trí trên trang khi xuất bản trình bày [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

The following example shows how to convert PowerPoint to TIFF with default size.

```csharp
[C#]
// Tạo một đối tượng Presentation đại diện cho một tệp bản trình bày
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Lưu bản trình bày thành tài liệu TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

The following example shows how to convert PowerPoint to TIFF with custom size.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho một tệp Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Khởi tạo lớp TiffOptions
    TiffOptions opts = new TiffOptions();
    // Thiết lập loại nén
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Các loại nén
    // Mặc định - Xác định chế độ nén mặc định (LZW).
    // Không - Xác định không nén.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Độ sâu phụ thuộc vào loại nén và không thể được đặt thủ công.
    // Resolution unit  is always equal to “2” (dots per inch)
    // Thiết lập DPI ảnh
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Đặt kích thước ảnh
    opts.ImageSize = new Size(1728, 1078);
    // Lưu bản trình bày thành TIFF với kích thước ảnh đã chỉ định
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

The following example shows how to convert PowerPoint to TIFF with custom image pixel format.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho một tệp Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat chứa các giá trị sau (như có thể thấy trong tài liệu):
    Format1bppIndexed; // 1 bit mỗi pixel, dạng chỉ mục.
    Format4bppIndexed; // 4 bit mỗi pixel, dạng chỉ mục.
    Format8bppIndexed; // 8 bit mỗi pixel, dạng chỉ mục.
    Format24bppRgb; // 24 bit mỗi pixel, RGB.
    Format32bppArgb; // 32 bit mỗi pixel, ARGB.
    */
    // Lưu bản trình bày thành TIFF với kích thước ảnh đã chỉ định
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [ITiffOptions](../itiffoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->