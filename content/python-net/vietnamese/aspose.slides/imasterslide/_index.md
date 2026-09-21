---
title: IMasterSlide class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/imasterslide/
---
## IMasterSlide lớp

Đại diện cho một slide master trong một bản trình chiếu.

Kiểu IMasterSlide tiết lộ các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/imasterslide/header_footer_manager/) | Trả về trình quản lý HeaderFooter của slide master.<br/>            Chỉ đọc [`IMasterSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/vi/aspose.slides/imasterslide/title_style/) | Trả về kiểu dáng của văn bản tiêu đề.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/vi/aspose.slides/imasterslide/body_style/) | Trả về kiểu dáng của văn bản nội dung.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/vi/aspose.slides/imasterslide/other_style/) | Trả về kiểu dáng của một văn bản khác.<br/>            Chỉ đọc [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/vi/aspose.slides/imasterslide/layout_slides/) | Trả về bộ sưu tập các slide bố cục con cho slide master này.<br/>            Chỉ đọc [`IMasterLayoutSlideCollection`](/slides/python-net/vi/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/vi/aspose.slides/imasterslide/preserve/) | Xác định xem master tương ứng có bị xóa khi tất cả <br/>            các slide theo sau master đó đều bị xóa hay không.<br/>            Lưu ý: Aspose.Slides sẽ không bao giờ tự động xóa bất kỳ master nào không được sử dụng, <br/>            để thực tế xóa các master không sử dụng, gọi **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Đọc/ghi **bool**. |
| [`has_depending_slides`](/slides/python-net/vi/aspose.slides/imasterslide/has_depending_slides/) | Trả về true nếu tồn tại ít nhất một slide phụ thuộc vào slide master này.<br/>            Chỉ đọc **bool**. |
| [`drawing_guides`](/slides/python-net/vi/aspose.slides/imasterslide/drawing_guides/) | Trả về một bộ sưu tập các hướng dẫn vẽ cho slide master.<br/>            Chỉ đọc [`IDrawingGuidesCollection`](/slides/python-net/vi/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/vi/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/vi/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/vi/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/vi/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/vi/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/vi/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/vi/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/imasterslide/theme_manager/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/vi/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Tạo một slide master mới dựa trên slide hiện tại, áp dụng một giao diện bên ngoài cho nó <br/>            và áp dụng slide master đã tạo cho tất cả các slide phụ thuộc. |
| [`get_depending_slides(self)`](/slides/python-net/vi/aspose.slides/imasterslide/get_depending_slides/#) | Trả về một mảng chứa tất cả các slide phụ thuộc vào slide master này. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/imasterslide/create_theme_effective/#) |  |


### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)