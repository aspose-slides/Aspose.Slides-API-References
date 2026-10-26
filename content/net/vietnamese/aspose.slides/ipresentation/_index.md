---
title: IPresentation
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Tài liệu trình chiếu
type: docs
weight: 6750
url: /vi/aspose.slides/ipresentation/
---
## IPresentation giao diện

Tài liệu trình chiếu

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Thuộc tính

| Tên | Mô tả |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình chiếu. Chỉ đọc [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Trả về giao diện IDisposable. Chỉ đọc IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Cho phép lấy giao diện IPresentationComponent cơ bản. Chỉ đọc [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Trả về tập hợp tất cả các tệp âm thanh được nhúng trong bản trình chiếu. Chỉ đọc [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Trả về tập hợp các tác giả bình luận. Chỉ đọc [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Trả về hoặc thiết lập ngày và giờ sẽ thay thế nội dung của các trường datetime. Thời gian tạo đối tượng Presentation này mặc định. Đọc/ghi DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Trả về dữ liệu tùy chỉnh của bản trình chiếu. Chỉ đọc [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Trả về kiểu văn bản mặc định cho các hình dạng. Chỉ đọc [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Trả về tập hợp các chữ ký được dùng để ký bản trình chiếu. Chỉ đọc [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu tiêu chuẩn và tùy chỉnh. Chỉ đọc [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Biểu thị số slide đầu tiên trong bản trình chiếu. Đọc/ghi Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Trả về trình quản lý phông chữ. Chỉ đọc [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Trả về trình quản lý HeaderFooter của bản trình chiếu. Chỉ đọc [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Cung cấp truy cập dễ dàng tới mọi siêu liên kết có trong tất cả các slide của bản trình chiếu (không bao gồm slide master, layout, notes). Chỉ đọc [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Trả về tập hợp tất cả các hình ảnh trong bản trình chiếu. Chỉ đọc [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Trả về danh sách tất cả các slide layout được định nghĩa trong bản trình chiếu. Chỉ đọc [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Trả về trình quản lý handout master. Chỉ đọc [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Trả về trình quản lý notes master. Chỉ đọc [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Trả về danh sách tất cả các slide master được định nghĩa trong bản trình chiếu. Chỉ đọc [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Trả về chủ đề master của bản trình chiếu. Chỉ đọc [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Trả về đối tượng kích thước slide notes. Chỉ đọc [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Lấy trình quản lý quyền cho bản trình chiếu này. Chỉ đọc [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Trả về tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu bản trình chiếu. Chỉ đọc [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Trả về danh sách tất cả các slide được định nghĩa trong bản trình chiếu. Chỉ đọc [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Trả về đối tượng kích thước slide. Chỉ đọc [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Trả về thông tin về định dạng mà bản trình chiếu được tải. Chỉ đọc [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Lấy dự án VBA có macro của bản trình chiếu. Đọc/ghi [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Trả về tập hợp tất cả các tệp video được nhúng trong bản trình chiếu. Chỉ đọc [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Lấy các thuộc tính xem toàn bộ bản trình chiếu. Chỉ đọc [`IViewProperties`](../iviewproperties). |

## Phương thức

| Tên | Mô tả |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Trả về các đối tượng Hình ảnh Thu nhỏ cho tất cả các slide của một bản trình chiếu. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Trả về các đối tượng Bitmap Thu nhỏ cho các slide được chỉ định của một bản trình chiếu. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Trả về các đối tượng Hình ảnh Thu nhỏ cho tất cả các slide của một bản trình chiếu với kích thước được chỉ định. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Trả về các đối tượng Hình ảnh Thu nhỏ cho tất cả các slide của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Trả về các đối tượng Hình ảnh Thu nhỏ cho các slide được chỉ định của một bản trình chiếu với kích thước được chỉ định. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Trả về các đối tượng Hình ảnh Thu nhỏ cho các slide được chỉ định của một bản trình chiếu với tỷ lệ tùy chỉnh. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Làm nổi bật tất cả các kết quả khớp của biểu thức chính quy với màu được chỉ định. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Làm nổi bật tất cả các kết quả khớp của văn bản mẫu với màu được chỉ định. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Làm nổi bật tất cả các kết quả khớp của văn bản mẫu với màu được chỉ định. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Ghép các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các hình dạng có thể chấp nhận trong mọi slide. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Thay thế tất cả các kết quả khớp của biểu thức chính quy bằng chuỗi được chỉ định. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Thay thế tất cả các lần xuất hiện của văn bản được chỉ định bằng một văn bản khác được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Lưu tất cả các slide của một bản trình chiếu thành một tập hợp các tệp đại diện cho markup XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Lưu tất cả các slide của một bản trình chiếu vào một stream theo định dạng được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Lưu tất cả các slide của một bản trình chiếu vào một tệp với định dạng được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Lưu các slide được chỉ định của một bản trình chiếu vào một stream theo định dạng được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Lưu tất cả các slide của một bản trình chiếu vào một stream theo định dạng được chỉ định và với các tùy chọn bổ sung. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Lưu tất cả các slide của một bản trình chiếu vào một tệp với định dạng được chỉ định và với các tùy chọn bổ sung. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Lưu các slide được chỉ định của một bản trình chiếu vào một stream theo định dạng được chỉ định. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Lưu các slide được chỉ định của một bản trình chiếu vào một tệp với định dạng được chỉ định. |

### Xem thêm

* giao diện [IPresentationComponent](../ipresentationcomponent)
* không gian tên [Aspose.Slides](../../aspose.slides)
* bộ lắp ráp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->