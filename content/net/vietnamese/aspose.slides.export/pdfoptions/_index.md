---
title: PdfOptions
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Cung cấp các tùy chọn điều khiển cách một bản trình chiếu được lưu ở định dạng Pdf.
type: docs
weight: 4330
url: /vi/aspose.slides.export/pdfoptions/
---
## PdfOptions lớp

Cung cấp các tùy chọn điều khiển cách một bản trình chiếu được lưu dưới dạng Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Hàm tạo

| Tên | Mô tả |
| --- | --- |
| [PdfOptions](pdfoptions)() | Phương thức khởi tạo mặc định. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Chứa một tập hợp các cờ xác định quyền truy cập nào sẽ được cấp khi tài liệu được mở với quyền người dùng. Xem [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Trả về hoặc đặt một mảng các tên font family do người dùng định nghĩa mà Aspose.Slides nên coi là chung. Đọc/ghi String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Áp dụng màu trong suốt chỉ định cho hình ảnh nếu `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Cho biết liệu nên tự động chọn chế độ nén hiệu quả nhất (thay vì chế độ mặc định) cho mỗi hình ảnh. Nếu đặt thành Boolean.true, đối với mỗi hình ảnh trong bản trình chiếu, thuật toán nén phù hợp nhất sẽ được chọn, dẫn đến kích thước tài liệu PDF kết quả nhỏ hơn. Việc lựa chọn tỉ lệ nén hình ảnh tốt nhất tốn tính toán và yêu cầu thêm RAM, và tùy chọn này mặc định là Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Mức độ tuân thủ mong muốn cho tài liệu PDF được tạo. Đọc/ghi [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp phông chữ nguồn không được tìm thấy. Đọc/ghi String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Đặt true để vẽ khung đen quanh mỗi slide. Đọc/ghi Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Xác định xem có nhúng tất cả các ký tự của phông chữ hay chỉ một phần được sử dụng. Đọc/ghi Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Xác định xem Aspose.Slides có nhúng các phông chữ chung cho văn bản ASCII (phạm vi mã 33..127) hay không. Các phông chữ cho mã ký tự lớn hơn 127 luôn được nhúng. Danh sách phông chữ chung bao gồm 14 phông chữ cơ bản của PDF và các phông chữ bổ sung do người dùng chỉ định. Đọc/ghi Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Trả về hoặc đặt kiểu hiển thị của gradient. Đọc/ghi [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Lấy hoặc đặt màu trong suốt của hình ảnh. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Đặt true để chuyển đổi tất cả dữ liệu OLE từ bản trình chiếu thành các tệp nhúng trong PDF kết quả. Đọc/ghi Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Cung cấp các tùy chọn điều khiển giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ-đọc [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Trả về hoặc đặt giá trị xác định chất lượng của các hình JPEG trong tài liệu PDF. Đọc/ghi Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Đặt mật khẩu người dùng để bảo vệ tài liệu PDF. Đọc/ghi String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Đại diện cho một đối tượng gọi lại để cập nhật tiến độ lưu dưới dạng phần trăm. Xem [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Cho biết liệu văn bản có nên được raster hóa thành bitmap và lưu vào PDF khi phông chữ không hỗ trợ kiểu in đậm hay không. Cách này có thể cải thiện chất lượng văn bản trong PDF kết quả cho một số phông chữ. Đọc/ghi Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Đặt true để chuyển đổi tất cả metafile được sử dụng trong bản trình chiếu sang hình PNG. Đọc/ghi Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Xác định có bỏ qua các siêu liên kết có gọi JavaScript khi lưu bản trình chiếu hay không. Đọc/ghi Boolean. Giá trị mặc định là **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Trả về hoặc đặt giá trị xác định độ phân giải của hình ảnh trong tài liệu PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Xác định loại nén sẽ được sử dụng cho toàn bộ nội dung văn bản trong tài liệu. Đọc/ghi [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Ví dụ

Ví dụ dưới đây minh họa cách chuyển PowerPoint sang PDF với các tùy chọn tùy chỉnh.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Khởi tạo lớp PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Đặt chất lượng Jpeg
	pdfOptions.JpegQuality = 90;
	// Đặt hành vi cho metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Đặt mức nén văn bản
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Xác định tiêu chuẩn PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Lưu bản trình chiếu dưới dạng PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Ví dụ dưới đây minh họa cách chuyển PowerPoint sang PDF với các slide ẩn.

```csharp
[C#]
// Khởi tạo một lớp Presentation đại diện cho tệp PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Khởi tạo lớp PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Thêm các slide ẩn
	pdfOptions.ShowHiddenSlides = true;
	// Lưu bản trình chiếu dưới dạng PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Ví dụ dưới đây minh họa cách chuyển PowerPoint sang PDF có bảo mật bằng mật khẩu.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Khởi tạo lớp PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Đặt mật khẩu PDF và quyền truy cập
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Lưu bản trình chiếu dưới dạng PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Ví dụ dưới đây minh họa cách chuyển PowerPoint sang PDF kèm ghi chú.

```csharp
[C#]
// Khởi tạo một đối tượng Presentation đại diện cho tệp bản trình chiếu
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Đặt Kiểu và Kích thước Slide
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Xem thêm

* lớp [SaveOptions](../saveoptions)
* giao diện [IPdfOptions](../ipdfoptions)
* không gian tên [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->