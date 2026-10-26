---
title: TiffOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn điều khiển cách một bài thuyết trình được lưu ở định dạng TIFF.
type: docs
weight: 4570
url: /vi/aspose.slides.export/tiffoptions/
---
## TiffOptions class

Cung cấp các tùy chọn điều khiển cách một bài thuyết trình được lưu ở định dạng TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructors

| Tên | Mô tả |
| --- | --- |
| [TiffOptions](tiffoptions)() | Hàm tạo mặc định. |

## Properties

| Tên | Mô tả |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. Tùy chọn này sẽ chỉ được áp dụng nếu [`CompressionType`](./compressiontype) được đặt thành CCITT4 hoặc CCITT3. Đọc/ghi [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Mặc định là Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Xác định loại nén. Đọc/ghi [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng khi không tìm thấy phông nguồn. Đọc/ghi String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Xác định độ phân giải chiều ngang tính bằng điểm trên inch. Đọc/ghi UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Xác định độ phân giải chiều dọc tính bằng điểm trên inch. Đọc/ghi UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu dáng trực quan của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Xác định kích thước của ảnh TIFF được tạo. Giá trị mặc định là 0x0, nghĩa là kích thước ảnh sẽ được tính dựa trên kích thước slide của bài thuyết trình. Đọc/ghi Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Cung cấp các tùy chọn điều khiển giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ đọc [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Xác định định dạng pixel cho các ảnh được tạo. Đọc/ghi [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho đối tượng callback dùng để lưu cập nhật tiến độ dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Xác định có bỏ qua các liên kết siêu văn bản có lời gọi JavaScript khi lưu bài thuyết trình không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bài thuyết trình [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Examples

Ví dụ sau cho thấy cách chuyển PowerPoint sang TIFF với kích thước mặc định.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp bài thuyết trình
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Lưu bài thuyết trình thành tài liệu TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Ví dụ sau cho thấy cách chuyển PowerPoint sang TIFF với kích thước tùy chỉnh.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Khởi tạo lớp TiffOptions
    TiffOptions opts = new TiffOptions();
    // Đặt loại nén
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Các loại nén
    // Default - Xác định sơ đồ nén mặc định (LZW).
    // None - Xác định không nén.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Độ sâu phụ thuộc vào loại nén và không thể đặt thủ công.
    // Đơn vị độ phân giải luôn bằng “2” (điểm trên inch)
    // Đặt DPI cho ảnh
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Đặt kích thước ảnh
    opts.ImageSize = new Size(1728, 1078);
    // Lưu bài thuyết trình thành TIFF với kích thước ảnh đã chỉ định
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Ví dụ sau cho thấy cách chuyển PowerPoint sang TIFF với định dạng pixel ảnh tùy chỉnh.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp Presentation
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
    // Lưu bài thuyết trình thành TIFF với kích thước ảnh đã chỉ định
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### See Also

* lớp [SaveOptions](../saveoptions)
* giao diện [ITiffOptions](../itiffoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->