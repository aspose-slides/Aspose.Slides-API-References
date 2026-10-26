---
title: SVGOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một tùy chọn SVG.
type: docs
weight: 4430
url: /vi/aspose.slides.export/svgoptions/
---
## Lớp SVGOptions

Đại diện cho tùy chọn SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Khởi tạo một thể hiện mới của lớp SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng bộ điều khiển nhúng liên kết. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Trả về cài đặt mặc định. Chỉ đọc [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Trả về cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. Chỉ đọc [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Trả về cài đặt cho việc tạo tệp SVG chính xác nhất. Chỉ đọc [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng khi không tìm thấy phông nguồn. Đọc-ghi String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Cờ boolean cho biết liệu các phần đã cắt còn lại như một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị loại bỏ; nếu false, chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc/ghi Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành `true`, các ligature sẽ bị tắt trong kết quả hiển thị. Mặc định, thuộc tính này được đặt thành `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Vô hiệu hoá việc tách gradient FromCornerX và FromCenter. Đọc/ghi Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 không có khả năng định nghĩa khoảng chèn cho các dấu đánh dấu. Động cơ ghi SVG của Aspose.Slides có cách giải quyết: nó cắt phần cuối của đường có mũi tên, do đó, đường không chồng lên các dấu đánh dấu. Tùy chọn này tắt hành vi đó. Đọc/ghi Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Xác định cách xử lý phông chữ được tải bên ngoài. Đọc/ghi [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu trực quan của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Cung cấp các tùy chọn điều khiển giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Xác định chất lượng mã hoá JPEG. Đọc/ghi Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Trả về hoặc đặt giới hạn độ phân giải thấp hơn cho việc raster hóa metafile. Đọc/ghi Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Đại diện cho mức độ nén hình ảnh |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho một đối tượng callback để lưu tiến độ cập nhật theo phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Trả về và đặt một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc/ghi [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Chỉ định liệu có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình chiếu hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Xác định liệu thực hiện việc xoay hình dạng đã chỉ định khi render hay không. Đọc/ghi Boolean. Giá trị mặc định là true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. Đọc/ghi Boolean. Giá trị mặc định là false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Xác định liệu văn bản trên slide có được lưu dưới dạng đồ họa hay không. Đọc/ ghi Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy bỏ. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [ISVGOptions](../isvgoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->