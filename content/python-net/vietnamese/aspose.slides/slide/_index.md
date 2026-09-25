---
title: Slide class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/slide/
---
## Lớp Slide

Đại diện cho một slide trong bài thuyết trình.

**Kế thừa:**[`Slide`](/slides/python-net/vi/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

Kiểu Slide cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/slide/shapes/) | Trả về các hình dạng của một slide.<br/>            Chỉ đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/slide/controls/) | Trả về bộ sưu tập các điều khiển ActiveX trên một slide.<br/>            Chỉ đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/slide/name/) | Trả về hoặc đặt tên của một slide.<br/>            Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/slide/slide_id/) | Trả về ID của một slide.<br/>            Chỉ đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/slide/custom_data/) | Trả về dữ liệu tùy chỉnh của slide.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/slide/timeline/) | Trả về đối tượng thời gian biểu hoạt ảnh.<br/>            Chỉ đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/slide/slide_show_transition/) | Trả về đối tượng Transition chứa thông tin về<br/>            cách slide được chỉ định tiến triển trong buổi chiếu slide.<br/>            Chỉ đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/slide/background/) | Trả về nền của slide.<br/>            Chỉ đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/slide/hyperlink_queries/) | Cung cấp truy cập dễ dàng tới các siêu liên kết chứa trong slide.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/slide/show_master_shapes/) | Xác định liệu các hình dạng trên master slide có được hiển thị trên các slide hay không.<br/>            Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/slide/presentation/) | Trả về giao diện IPresentation.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/slide/header_footer_manager/) | Trả về trình quản lý HeaderFooter của slide.<br/>            Chỉ đọc [`ISlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/slide/theme_manager/) | Trả về trình quản lý chủ đề ghi đè.<br/>            Chỉ đọc [`IOverrideThemeManager`](/slides/python-net/vi/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/vi/aspose.slides/slide/slide_number/) | Trả về số thứ tự của slide.<br/>            Chỉ mục của slide trong bộ sưu tập [`Presentation.slides`](/slides/python-net/vi/aspose.slides/presentation/slides) luôn bằng SlideNumber - Presentation.FirstSlideNumber.<br/>            Đọc/ghi **int**. |
| [`hidden`](/slides/python-net/vi/aspose.slides/slide/hidden/) | Xác định liệu slide được chỉ định có bị ẩn trong buổi chiếu slide hay không.<br/>            Đọc/ghi **bool**. |
| [`layout_slide`](/slides/python-net/vi/aspose.slides/slide/layout_slide/) | Trả về hoặc đặt layout slide cho slide hiện tại.<br/>            Đọc/ghi [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/vi/aspose.slides/slide/notes_slide_manager/) | Cho phép truy cập slide ghi chú, thêm và xóa nó.<br/>            Chỉ đọc [`INotesSlideManager`](/slides/python-net/vi/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/vi/aspose.slides/slide/slide/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/slide/join_portions_with_same_formatting/#) | Nối các run có cùng định dạng trong tất cả các đoạn trong mọi hình dạng cho phép. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Nối các run có cùng định dạng trong tất cả các đoạn trong mọi hình dạng cho phép. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/slide/get_image/#float-float) | Trả về một đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/slide/get_image/#) | Trả về một đối tượng Thumbnail Image (20% kích thước thực). |
| [`get_image(self, image_size)`](/slides/python-net/vi/aspose.slides/slide/get_image/#asposeslidessize) | Trả về một đối tượng Thumbnail Image với kích thước chỉ định. |
| [`get_image(self, options)`](/slides/python-net/vi/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Trả về một đối tượng ảnh tiff Thumbnail với các tham số chỉ định. |
| [`get_image(self, options)`](/slides/python-net/vi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Trả về một đối tượng Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Trả về một đối tượng Thumbnail Image với tỷ lệ tùy chỉnh. |
| [`get_image(self, options, image_size)`](/slides/python-net/vi/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Trả về một đối tượng Thumbnail Image với kích thước chỉ định. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/slide/write_as_svg/#iorawiobase) | Lưu nội dung slide dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung slide dưới dạng tệp SVG. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/slide/equals/#ibaseslide) | Xác định liệu hai đối tượng IBaseSlide có bằng nhau hay không.<br/>            Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide.<br/>            Hai slide bằng nhau nếu tất cả các hình dạng, kiểu, văn bản, hoạt ảnh và các thiết lập khác, v.v. đều bằng nhau. So sánh không xét các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/slide/create_theme_effective/#) | Trả về một chủ đề hiệu quả cho slide này. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/slide/find_shape_by_alt_text/#str) | Tìm lần xuất hiện đầu tiên của một hình dạng có văn bản thay thế được chỉ định. |
| [`write_as_emf(self, stream)`](/slides/python-net/vi/aspose.slides/slide/write_as_emf/#iorawiobase) | Lưu nội dung slide dưới dạng tệp EMF. |
| [`remove(self)`](/slides/python-net/vi/aspose.slides/slide/remove/#) | Xóa slide khỏi bài thuyết trình. |
| [`reset(self)`](/slides/python-net/vi/aspose.slides/slide/reset/#) | Đặt lại vị trí, kích thước và định dạng của mọi hình dạng có nguyên mẫu trên LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/vi/aspose.slides/slide/get_slide_comments/#icommentauthor) | Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể. |

### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`Slide`](/slides/python-net/vi/aspose.slides/slide)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)