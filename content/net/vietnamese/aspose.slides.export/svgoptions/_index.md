---
title: SVGOptions
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Biểu diễn một tùy chọn SVG.
type: docs
weight: 4450
url: /vi/aspose.slides.export/svgoptions/
---
## SVGOptions lớp

Represents an SVG options.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Các hàm tạo

| Tên | Mô tả |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Khởi tạo một thể hiện mới của lớp SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Khởi tạo một thể hiện mới của lớp SVGOptions, chỉ định đối tượng bộ điều khiển nhúng liên kết ILinkEmbedController. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Trả về cài đặt mặc định. Chỉ đọc [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Trả về cài đặt cho việc tạo tệp SVG đơn giản nhất và nhỏ nhất. Chỉ đọc [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Trả về cài đặt cho việc tạo tệp SVG chính xác nhất. Chỉ đọc [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc thiết lập phông chữ được sử dụng khi không tìm thấy phông chữ nguồn. Đọc-ghi String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Một cờ boolean cho biết liệu các phần đã cắt sẽ vẫn là một phần của tài liệu hay không. Nếu true, các phần đã cắt sẽ bị loại bỏ; nếu false, chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Xác định liệu văn bản 3D có bị tắt trong SVG hay không. Đọc-ghi Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Lấy hoặc đặt giá trị cho biết liệu văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành `true`, ligature sẽ bị tắt trong đầu ra được render. Mặc định, thuộc tính này được đặt thành `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Tắt việc tách gradient FromCornerX và FromCenter. Đọc-ghi Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 thiếu khả năng định nghĩa các inset cho marker. Động cơ viết SVG của Aspose.Slides có biện pháp khắc phục cho vấn đề này: nó cắt phần cuối của đường có mũi tên, do đó, đường không chồng lên marker. Tùy chọn này tắt hành vi đó. Đọc-ghi Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Xác định cách xử lý phông chữ được tải ngoại vi. Đọc-ghi [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc thiết lập kiểu hiển thị của gradient. Đọc-ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Cung cấp các tùy chọn kiểm soát giao diện của đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Xác định chất lượng mã hoá JPEG. Đọc-ghi Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Trả về hoặc thiết lập giới hạn độ phân giải thấp nhất cho raster hoá metafile. Đọc-ghi Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Biểu diễn mức nén của hình ảnh |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Biểu diễn một đối tượng callback để lưu cập nhật tiến độ dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Trả về và thiết lập một giao diện callback cho phép người dùng kiểm soát việc chuyển đổi hình dạng. Đọc-ghi [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Chỉ định liệu có bỏ qua liên kết siêu văn bản có lời gọi JavaScript khi lưu bản trình chiếu hay không. Đọc-ghi Boolean. Giá trị mặc định là **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Xác định liệu có thực hiện việc quay hình dạng đã chỉ định khi render hay không. Đọc-ghi Boolean. Giá trị mặc định là true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Xác định liệu khung văn bản có được bao gồm trong khu vực render hay không. Đọc-ghi Boolean. Giá trị mặc định là false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Xác định liệu văn bản trên slide sẽ được lưu dưới dạng đồ họa hay không. Đọc-ghi Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quy trình tải sẽ tiếp tục hay bị hủy. Đọc-ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [ISVGOptions](../isvgoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* bộ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->