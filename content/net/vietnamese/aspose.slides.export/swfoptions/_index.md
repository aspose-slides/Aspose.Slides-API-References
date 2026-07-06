---
title: SwfOptions
second_title: Aspose.Sildes cho .NET Tài liệu tham khảo API
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Swf.
type: docs
weight: 4530
url: /vi/aspose.slides.export/swfoptions/
---
## Lớp SwfOptions

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Các hàm tạo

| Tên | Mô tả |
| --- | --- |
| [SwfOptions](swfoptions)() | Hàm tạo mặc định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Xác định xem tài liệu SWF được tạo có được nén hay không. Mặc định là `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được dùng khi không tìm thấy phông nguồn. Đọc/ghi String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Bật/tắt trình đơn ngữ cảnh. Mặc định là true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu dáng trực quan của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Xác định chất lượng của ảnh JPEG. Mặc định là 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh phải là PNG 32x64 pixel, nếu không logo có thể hiển thị không đúng. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. Chỉ có tác dụng nếu một [`LogoImageBytes`](./logoimagebytes) được chỉ định. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Hiển thị/ẩn khung dưới. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Hiển thị/ẩn nút toàn màn hình. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Hiển thị/ẩn khung trái. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Xác định xem có nên hiển thị viền quanh các trang hay không. Mặc định là true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Hiển thị/ẩn bộ chuyển trang. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Hiển thị/ẩn phần tìm kiếm. Có thể ghi đè trong flashvars. Mặc định là true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Hiển thị/ẩn toàn bộ khung trên cùng. Có thể ghi đè trong flashvars. Mặc định là true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Xác định xem có bỏ qua các siêu liên kết gọi JavaScript khi lưu bản trình chiếu hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](../islideslayoutoptions). Thuộc tính này không hỗ trợ gán đối tượng có kiểu [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Bắt đầu với khung trái đã mở. Có thể ghi đè trong flashvars. Mặc định là false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Xác định xem tài liệu SWF được tạo có bao gồm trình xem tài liệu tích hợp hay không. Mặc định là `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

Ví dụ sau cho thấy cách chuyển đổi PowerPoint sang SWF Flash.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp bản trình chiếu
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Lưu bản trình chiếu và các trang ghi chú
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Xem thêm

* class [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->