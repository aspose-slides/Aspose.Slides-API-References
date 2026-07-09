---
title: Presentation
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Biểu diễn một bản trình chiếu Microsoft PowerPoint.
type: docs
weight: 9590
url: /vi/aspose.slides/presentation/
---
## Lớp Presentation

Biểu diễn một bản trình chiếu Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Các hàm tạo

| Tên | Mô tả |
| --- | --- |
| [Presentation](presentation#constructor)() | Hàm tạo này tạo một bản trình chiếu mới từ đầu. Bản trình chiếu được tạo có một slide trống. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Hàm tạo này tạo một bản trình chiếu mới từ đầu. Bản trình chiếu được tạo có một slide trống. |
| [Presentation](presentation#constructor_2)(Stream) | Hàm tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [Presentation](presentation#constructor_4)(string) | Hàm tạo này nhận đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Hàm tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Hàm tạo này nhận đường dẫn tệp nguồn mà từ đó nội dung của Presentation được đọc. |

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. Chỉ đọc [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Trả về tập hợp của tất cả các tệp âm thanh được nhúng trong bản trình chiếu. Chỉ đọc [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Trả về tập hợp các tác giả bình luận. Chỉ đọc [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này theo mặc định. Đọc/ghi DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Trả về dữ liệu tùy chỉnh của bản trình chiếu. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Trả về kiểu văn bản mặc định cho các hình dạng. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Trả về tập hợp các chữ ký được sử dụng để ký bản trình chiếu. Chỉ đọc [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu tiêu chuẩn và tùy chỉnh. Chỉ đọc [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Biểu diễn số slide đầu tiên trong bản trình chiếu |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Trả về trình quản lý phông chữ. Chỉ đọc [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter hiện tại. Chỉ đọc [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Cung cấp truy cập dễ dàng tới tất cả các siêu liên kết có trong tất cả các slide của bản trình chiếu (không bao gồm master, layout, notes slides). Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Trả về tập hợp của tất cả các hình ảnh trong bản trình chiếu. Chỉ đọc [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Trả về danh sách tất cả các layout slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Trả về trình quản lý handout master. Chỉ đọc [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Trả về trình quản lý notes master. Chỉ đọc [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Trả về danh sách tất cả các master slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Trả về chủ đề master. Chỉ đọc [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Trả về đối tượng kích thước slide ghi chú. Chỉ đọc [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Lấy trình quản lý quyền cho bản trình chiếu này. Chỉ đọc [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Trả về tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu bản trình chiếu. Chỉ đọc [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Trả về cài đặt trình chiếu cho bản trình chiếu. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Trả về đối tượng kích thước slide. Chỉ đọc [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Trả về thông tin về định dạng mà bản trình chiếu được tải. Chỉ đọc [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Lấy hoặc đặt dự án VBA với macro của bản trình chiếu. Đọc/ghi [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Trả về tập hợp của tất cả các tệp video được nhúng trong bản trình chiếu. Chỉ đọc [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Lấy các thuộc tính xem toàn cục của bản trình chiếu. Chỉ đọc [`IViewProperties`](../iviewproperties). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Giải phóng tất cả tài nguyên được sử dụng bởi đối tượng Presentation này. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Trả về các đối tượng Image cho tất cả các slide của một bản trình chiếu. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với kích thước được chỉ định. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với kích thước được chỉ định. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Làm nổi bật tất cả các kết quả phù hợp của biểu thức chính quy với màu được chỉ định. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Làm nổi bật tất cả các kết quả phù hợp của văn bản mẫu với màu được chỉ định. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Làm nổi bật tất cả các kết quả phù hợp của văn bản mẫu với màu được chỉ định. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Nối các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các hình dạng chấp nhận được trên tất cả các slide. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Thay thế tất cả các kết quả phù hợp của biểu thức chính quy bằng chuỗi được chỉ định. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Thay thế tất cả các lần xuất hiện của văn bản được chỉ định bằng một văn bản khác được chỉ định. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Lưu tất cả các slide của một bản trình chiếu thành một tập hợp các tệp đại diện cho markup XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Lưu tất cả các slide của một bản trình chiếu vào một stream ở định dạng được chỉ định. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Lưu tất cả các slide của một bản trình chiếu vào một tệp với định dạng được chỉ định. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Lưu các slide được chỉ định của một bản trình chiếu vào một stream ở định dạng được chỉ định và giữ số trang. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Lưu tất cả các slide của một bản trình chiếu vào một stream ở định dạng được chỉ định và với các tùy chọn bổ sung. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng được chỉ định và giữ số trang. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Lưu các slide được chỉ định của một bản trình chiếu vào một stream ở định dạng được chỉ định và giữ số trang. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng được chỉ định và giữ số trang. |

### Ví dụ

Ví dụ sau đây cho thấy cách tạo PowerPoint Presentation.

```csharp
[C#]
// Tạo một đối tượng Presentation đại diện cho tệp trình chiếu
using (Presentation presentation = new Presentation())
{
    // Lấy slide đầu tiên
    ISlide slide = presentation.Slides[0];
    // Thêm một autoshape kiểu line
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Lưu tệp trình chiếu.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Ví dụ sau đây cho thấy cách mở và lưu Presentation.

```csharp
[C#]
// Tải bất kỳ tệp được hỗ trợ nào trong Presentation, ví dụ ppt, pptx, odp, v.v.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Lưu tệp trình chiếu.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Xem thêm

* giao diện [IPresentation](../ipresentation)
* không gian tên [Aspose.Slides](../../aspose.slides)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->