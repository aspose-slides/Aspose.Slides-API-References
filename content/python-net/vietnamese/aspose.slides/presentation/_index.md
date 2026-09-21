---
title: Presentation class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentation/
---
## Lớp Presentation

Biểu diễn một bản trình bày Microsoft PowerPoint.

Kiểu Presentation cung cấp các thành viên sau:

## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#) | Hàm khởi tạo này tạo một bản trình bày mới từ đầu.<br/>            Bản trình bày được tạo có một slide trống. |
| [`__init__(self, load_options)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#loadoptions) | Hàm khởi tạo này tạo một bản trình bày mới từ đầu.<br/>            Bản trình bày được tạo có một slide trống. |
| [`__init__(self, stream)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#iorawiobase) | Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [`__init__(self, stream, load_options)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Hàm khởi tạo này là cơ chế chính để đọc một Presentation hiện có. |
| [`__init__(self, file)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#str) | Hàm khởi tạo này nhận đường dẫn tệp nguồn từ đó<br/>             nội dung của Presentation được đọc. |
| [`__init__(self, file, load_options)`](/slides/python-net/vi/aspose.slides/presentation/__init__/#str-loadoptions) | Hàm khởi tạo này nhận đường dẫn tệp nguồn từ đó<br/>            nội dung của Presentation được đọc. |

## Các thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`current_date_time`](/slides/python-net/vi/aspose.slides/presentation/current_date_time/) | Trả về hoặc đặt ngày và giờ sẽ thay thế nội dung của các trường datetime.<br/>            Thời gian tạo đối tượng Presentation này theo mặc định.<br/>            Đọc/ghi **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/presentation/header_footer_manager/) | Trả về bộ quản lý HeaderFooter hiện tại.<br/>            Chỉ đọc [`IPresentationHeaderFooterManager`](/slides/python-net/vi/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/vi/aspose.slides/presentation/protection_manager/) | Lấy bộ quản lý quyền cho bản trình bày này.<br/>            Chỉ đọc [`IProtectionManager`](/slides/python-net/vi/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/vi/aspose.slides/presentation/slides/) | Trả về danh sách tất cả các slide được định nghĩa trong bản trình bày.<br/vi/>            Chỉ đọc [`ISlideCollection`](/slides/python-net/vi/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/vi/aspose.slides/presentation/sections/) | Trả về danh sách tất cả các phần slide được định nghĩa trong bản trình bày.<br/>            Chỉ đọc [`ISectionCollection`](/slides/python-net/vi/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/vi/aspose.slides/presentation/slide_size/) | Trả về đối tượng kích thước slide.<br/>            Chỉ đọc [`ISlideSize`](/slides/python-net/vi/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/vi/aspose.slides/presentation/notes_size/) | Trả về đối tượng kích thước slide ghi chú.<br/>            Chỉ đọc [`INotesSize`](/slides/python-net/vi/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/vi/aspose.slides/presentation/layout_slides/) | Trả về danh sách tất cả các slide bố cục được định nghĩa trong bản trình bày.<br/>            Chỉ đọc [`IGlobalLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/vi/aspose.slides/presentation/masters/) | Trả về danh sách tất cả các slide chủ đề được định nghĩa trong bản trình bày.<br/>            Chỉ đọc [`IMasterSlideCollection`](/slides/python-net/vi/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/vi/aspose.slides/presentation/master_notes_slide_manager/) | Trả về bộ quản lý notes master.<br/>            Chỉ đọc [`IMasterNotesSlideManager`](/slides/python-net/vi/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/vi/aspose.slides/presentation/master_handout_slide_manager/) | Trả về bộ quản lý handout master.<br/>            Chỉ đọc [`IMasterHandoutSlideManager`](/slides/python-net/vi/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/vi/aspose.slides/presentation/fonts_manager/) | Trả về bộ quản lý phông chữ.<br/>            Chỉ đọc [`IFontsManager`](/slides/python-net/vi/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/vi/aspose.slides/presentation/default_text_style/) | Trả về kiểu văn bản mặc định cho các shape.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/vi/aspose.slides/presentation/comment_authors/) | Trả về tập hợp các tác giả bình luận.<br/>            Chỉ đọc [`ICommentAuthorCollection`](/slides/python-net/vi/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/vi/aspose.slides/presentation/document_properties/) | Trả về đối tượng DocumentProperties chứa các thuộc tính tài liệu tiêu chuẩn và tùy chỉnh.<br/>            Chỉ đọc [`IDocumentProperties`](/slides/python-net/vi/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/vi/aspose.slides/presentation/images/) | Trả về tập hợp tất cả các hình ảnh trong bản trình bày.<br/>            Chỉ đọc [`IImageCollection`](/slides/python-net/vi/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/vi/aspose.slides/presentation/audios/) | Trả về tập hợp tất cả các tệp âm thanh nhúng trong bản trình bày.<br/>            Chỉ đọc [`IAudioCollection`](/slides/python-net/vi/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/vi/aspose.slides/presentation/videos/) | Trả về tập hợp tất cả các tệp video nhúng trong bản trình bày.<br/>            Chỉ đọc [`IVideoCollection`](/slides/python-net/vi/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/vi/aspose.slides/presentation/slide_show_settings/) | Trả về cài đặt trình chiếu cho bản trình bày. |
| [`digital_signatures`](/slides/python-net/vi/aspose.slides/presentation/digital_signatures/) | Trả về tập hợp các chữ ký được dùng để ký bản trình bày.<br/>            Chỉ đọc [`IDigitalSignatureCollection`](/slides/python-net/vi/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/presentation/custom_data/) | Trả về dữ liệu tùy chỉnh của bản trình bày.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/vi/aspose.slides/presentation/all_custom_xml_parts/) | Trả về tất cả các phần dữ liệu tùy chỉnh trong bản trình bày.<br/>            Chỉ đọc [`ICustomXmlPart`](/slides/python-net/vi/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/vi/aspose.slides/presentation/vba_project/) | Lấy hoặc đặt dự án VBA với macro của bản trình bày.<br/>            Đọc/ghi [`IVbaProject`](/slides/python-net/vi/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/presentation/hyperlink_queries/) | Cung cấp truy cập dễ dàng tới tất cả siêu liên kết trong các slide của bản trình bày (không bao gồm master, layout, notes slides).<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/vi/aspose.slides/presentation/view_properties/) | Lấy các thuộc tính xem toàn bộ bản trình bày.<br/>            Chỉ đọc [`IViewProperties`](/slides/python-net/vi/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/vi/aspose.slides/presentation/first_slide_number/) | Biểu diễn số slide đầu tiên trong bản trình bày |
| [`sensitivity_labels`](/slides/python-net/vi/aspose.slides/presentation/sensitivity_labels/) | Trả về tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu bản trình bày.<br/>            Chỉ đọc [`ISensitivityLabelCollection`](/slides/python-net/vi/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/vi/aspose.slides/presentation/source_format/) | Trả về thông tin về định dạng mà bản trình bày được tải.<br/>            Chỉ đọc [`SourceFormat`](/slides/python-net/vi/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/vi/aspose.slides/presentation/master_theme/) | Trả về chủ đề master.<br/>            Chỉ đọc [`IMasterTheme`](/slides/python-net/vi/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/vi/aspose.slides/presentation/presentation/) |  |

## Các phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/vi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Lưu tất cả các slide của bản trình bày vào một tệp với định dạng được chỉ định. |
| [`save(self, stream, format)`](/slides/python-net/vi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Lưu tất cả các slide của bản trình bày vào một stream với định dạng được chỉ định. |
| [`save(self, fname, format, options)`](/slides/python-net/vi/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/vi/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Lưu tất cả các slide của bản trình bày vào một stream với định dạng được chỉ định và với các tùy chọn bổ sung. |
| [`save(self, options)`](/slides/python-net/vi/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Lưu tất cả các slide của bản trình bày vào một tập hợp các tệp biểu diễn markup XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/vi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Lưu các slide được chỉ định của bản trình bày vào một tệp với định dạng được chỉ định, giữ số trang. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/vi/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Lưu các slide được chỉ định của bản trình bày vào một tệp với định dạng được chỉ định, giữ số trang. |
| [`save(self, stream, slides, format)`](/slides/python-net/vi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Lưu các slide được chỉ định của bản trình bày vào một stream với định dạng được chỉ định, giữ số trang. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/vi/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Lưu các slide được chỉ định của bản trình bày vào một stream với định dạng được chỉ định, giữ số trang. |
| [`get_images(self, options)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Trả về các đối tượng Image cho tất cả các slide của bản trình bày. |
| [`get_images(self, options, slides)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của bản trình bày. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình bày với tỷ lệ tùy chỉnh. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của bản trình bày với tỷ lệ tùy chỉnh. |
| [`get_images(self, options, image_size)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Trả về các đối tượng Thumbnail Image cho tất cả các slide của bản trình bày với kích thước được chỉ định. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/vi/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Trả về các đối tượng Thumbnail Image cho các slide được chỉ định của bản trình bày với kích thước được chỉ định. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/vi/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Đánh dấu tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/vi/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Đánh dấu tất cả các khớp của văn bản mẫu với màu được chỉ định. |
| [`get_slide_by_id(self, id)`](/slides/python-net/vi/aspose.slides/presentation/get_slide_by_id/#int) | Trả về một Slide, MasterSlide hoặc LayoutSlide theo Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/presentation/join_portions_with_same_formatting/#) | Nối các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các shape chấp nhận được trên mọi slide. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/vi/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Đánh dấu tất cả các khớp của biểu thức chính quy với màu được chỉ định. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/vi/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Thay thế tất cả các lần xuất hiện của văn bản chỉ định bằng một văn bản khác được chỉ định. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/vi/aspose.slides/presentation/replace_regex/#str-str) | Thay thế tất cả các khớp của biểu thức chính quy bằng chuỗi được chỉ định. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)