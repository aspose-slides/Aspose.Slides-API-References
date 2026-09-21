---
title: ISlide class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/islide/
---
## ISlide lớp

Biểu diễn một slide trong bài thuyết trình.

Kiểu ISlide cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/islide/header_footer_manager/) | Trả về trình quản lý HeaderFooter của slide.<br/>            Chỉ đọc [`ISlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/vi/aspose.slides/islide/slide_number/) | Trả về số slide.<br/>            Chỉ số của slide trong bộ sưu tập [`IPresentation.slides`](/slides/python-net/vi/aspose.slides/ipresentation/slides) luôn bằng SlideNumber - 1.<br/>            Đọc/ghi **int**. |
| [`hidden`](/slides/python-net/vi/aspose.slides/islide/hidden/) | Xác định liệu slide đã chỉ định có bị ẩn trong buổi trình chiếu hay không.<br/>            Đọc/ghi **bool**. |
| [`layout_slide`](/slides/python-net/vi/aspose.slides/islide/layout_slide/) | Trả về hoặc thiết lập slide bố cục cho slide hiện tại.<br/>            Đọc/ghi [`ILayoutSlide`](/slides/python-net/vi/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/vi/aspose.slides/islide/notes_slide_manager/) | Cho phép truy cập slide ghi chú, thêm và xóa nó.<br/>            Chỉ đọc [`INotesSlideManager`](/slides/python-net/vi/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/vi/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/vi/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/vi/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/vi/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/vi/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/islide/theme_manager/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/islide/get_image/#float-float) | Trả về một đối tượng hình ảnh với tỷ lệ tùy chỉnh. |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/islide/get_image/#) | Trả về một đối tượng Hình ảnh Thu nhỏ (20% kích thước thực). |
| [`get_image(self, image_size)`](/slides/python-net/vi/aspose.slides/islide/get_image/#asposepydrawingsize) | Trả về một đối tượng hình ảnh với kích thước được chỉ định. |
| [`get_image(self, options)`](/slides/python-net/vi/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Trả về một đối tượng Bitmap tiff Thu nhỏ với các tham số được chỉ định. |
| [`get_image(self, options)`](/slides/python-net/vi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Trả về một đối tượng Bitmap Thu nhỏ. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Trả về một đối tượng Bitmap Thu nhỏ với tỷ lệ tùy chỉnh. |
| [`get_image(self, options, image_size)`](/slides/python-net/vi/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Trả về một đối tượng Bitmap Thu nhỏ với kích thước được chỉ định. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/islide/write_as_svg/#iorawiobase) | Lưu nội dung slide dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung slide dưới dạng tệp SVG. |
| [`get_slide_comments(self, author)`](/slides/python-net/vi/aspose.slides/islide/get_slide_comments/#icommentauthor) | Trả về tất cả các bình luận slide được thêm bởi tác giả cụ thể. |
| [`write_as_emf(self, stream)`](/slides/python-net/vi/aspose.slides/islide/write_as_emf/#iorawiobase) | Lưu nội dung slide dưới dạng tệp EMF. |
| [`remove(self)`](/slides/python-net/vi/aspose.slides/islide/remove/#) | Xóa slide khỏi bài thuyết trình. |
| [`reset(self)`](/slides/python-net/vi/aspose.slides/islide/reset/#) | Đặt lại vị trí, kích thước và định dạng của mọi hình dạng có nguyên mẫu trên LayoutSlide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/islide/create_theme_effective/#) |  |

### Xem Thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)