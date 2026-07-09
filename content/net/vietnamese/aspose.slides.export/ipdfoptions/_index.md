---
title: IPdfOptions
second_title: Aspose.Sildes cho .NET Tham chiếu API
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Pdf.
type: docs
weight: 4000
url: /vi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions giao diện

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Chứa một tập các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Trả về hoặc thiết lập một mảng các tên phông chữ do người dùng định nghĩa mà Aspose.Slides nên coi là chung. Đọc/ghi String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Áp dụng màu trong suốt đã chỉ định cho hình ảnh nếu `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Trả về giao diện ISaveOptions. Chỉ-đọc [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Cho biết liệu có nên tự động chọn mức nén hiệu quả nhất (thay vì mặc định) cho mỗi hình ảnh hay không. Nếu đặt thành Boolean.true, đối với mỗi hình ảnh trong bản trình chiếu, thuật toán nén phù hợp nhất sẽ được chọn, dẫn đến kích thước PDF kết quả nhỏ hơn. Việc chọn tỉ lệ nén hình ảnh tối ưu tốn nhiều tài nguyên tính toán và sử dụng thêm RAM, và tùy chọn này mặc định là Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Mức tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/ghi [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True để vẽ khung đen quanh mỗi slide. Đọc/ghi Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Xác định liệu tất cả ký tự của phông chữ có nên được nhúng hay chỉ một tập con được sử dụng. Đọc/ghi Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True để nhúng phông chữ TrueType cho các ký tự ASCII 32-127. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Đọc/ghi Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Lấy hoặc đặt màu trong suốt của hình ảnh. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu sang các tệp được nhúng trong PDF kết quả. Đọc/ghi Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ-đọc [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Trả về hoặc thiết lập giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Cho biết liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách tiếp cận này có thể nâng cao chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/ghi Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True để chuyển đổi tất cả các metafile được sử dụng trong bản trình chiếu sang hình ảnh PNG. Đọc/ghi Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Xác định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Trả về hoặc thiết lập giá trị xác định độ phân giải của các hình ảnh trong tài liệu PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. Đọc/ghi [`PdfTextCompression`](../pdftextcompression). |

### Xem Thêm

* giao diện [ISaveOptions](../isaveoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->