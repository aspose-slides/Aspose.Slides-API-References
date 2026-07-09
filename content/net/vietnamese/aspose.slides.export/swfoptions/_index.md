---
title: SwfOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng Swf.
type: docs
weight: 4530
url: /vi/aspose.slides.export/swfoptions/
---
## SwfOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [SwfOptions](swfoptions)() | Hàm tạo mặc định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Chỉ định liệu tài liệu SWF được tạo ra có nên nén hay không. Mặc định là `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. String đọc-ghi. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Bật/tắt menu ngữ cảnh. Mặc định là true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu dáng trực quan của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Chỉ định chất lượng của ảnh JPEG. Mặc định là 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh nên là PNG kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Lấy hoặc đặt địa chỉ hyperlink đầy đủ cho logo. Chỉ có hiệu lực nếu [`LogoImageBytes`](./logoimagebytes) được chỉ định. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho một đối tượng callback để cập nhật tiến trình lưu dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Hiển thị/ẩn khung dưới. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Hiển thị/ẩn nút toàn màn hình. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Chỉ định liệu tài liệu được tạo ra có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Hiển thị/ẩn khung bên trái. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Chỉ định liệu viền bao quanh các trang có nên hiển thị hay không. Mặc định là true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Hiển thị/ẩn bộ chuyển trang. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Hiển thị/ẩn phần tìm kiếm. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Hiển thị/ẩn toàn bộ khung trên. Có thể ghi đè trong flashvars. Mặc định là true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Chỉ định liệu có bỏ qua các hyperlink có lời gọi JavaScript khi lưu bản trình bày hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp đặt các slide trên trang khi xuất bản trình bày [`ISlidesLayoutOptions`](../islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Bắt đầu với khung trái đã mở. Có thể ghi đè trong flashvars. Mặc định là false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Chỉ định liệu tài liệu SWF được tạo ra có bao gồm trình xem tài liệu tích hợp hay không. Mặc định là `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

Ví dụ sau minh họa cách chuyển đổi PowerPoint sang SWF Flash.

```csharp
[C#]
// Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Lưu trình chiếu và các trang ghi chú
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [ISwfOptions](../iswfoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->