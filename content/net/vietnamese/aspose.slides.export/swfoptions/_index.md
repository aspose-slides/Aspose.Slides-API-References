---
title: SwfOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới định dạng Swf.
type: docs
weight: 4550
url: /vi/aspose.slides.export/swfoptions/
---
## SwfOptions lớp

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới định dạng Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Hàm khởi tạo

| Tên | Mô tả |
| --- | --- |
| [SwfOptions](swfoptions)() | Hàm khởi tạo mặc định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Chỉ định xem tài liệu SWF được tạo có nên được nén hay không. Mặc định là `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn. Đọc-ghi String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Bật/tắt menu ngữ cảnh. Mặc định là true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu hiển thị của gradient. Đọc-ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Chỉ định chất lượng của hình ảnh JPEG. Mặc định là 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh nên là ảnh PNG kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. Chỉ có tác dụng nếu một [`LogoImageBytes`](./logoimagebytes) được chỉ định. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Biểu diễn một đối tượng callback cho việc cập nhật tiến độ lưu dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Hiển thị/ẩn bảng dưới cùng. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Hiển thị/ẩn nút toàn màn hình. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Chỉ định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Hiển thị/ẩn bảng bên trái. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Chỉ định xem viền quanh các trang có nên được hiển thị hay không. Mặc định là true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Hiển thị/ẩn bộ chuyển trang. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Hiển thị/ẩn phần tìm kiếm. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Hiển thị/ẩn toàn bộ bảng trên cùng. Có thể bị ghi đè trong flashvars. Mặc định là true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Chỉ định có nên bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. Đọc-ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình bày [`ISlidesLayoutOptions`](../islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Bắt đầu với bảng bên trái đã mở. Có thể bị ghi đè trong flashvars. Mặc định là false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Chỉ định xem tài liệu SWF được tạo có nên bao gồm trình xem tài liệu tích hợp hay không. Mặc định là `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định việc quá trình tải sẽ tiếp tục hay bị hủy. Đọc-ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

Ví dụ sau đây minh họa cách chuyển đổi PowerPoint sang SWF Flash.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp bản trình bày
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Lưu bản trình bày và các trang ghi chú
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