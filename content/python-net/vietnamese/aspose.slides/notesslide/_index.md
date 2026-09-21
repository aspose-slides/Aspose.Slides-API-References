---
title: NotesSlide class
second_title: Aspose.Slides cho Python qua .NET API Tham chiếu
description: 
type: docs
url: /vi/aspose.slides/notesslide/
---
## NotesSlide lớp

Represents a notes slide in a presentation.

**Kế thừa:**[`NotesSlide`](/slides/python-net/vi/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

The NotesSlide type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/notesslide/shapes/) | Trả về các hình dạng của một slide.<br/>            Chỉ đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/notesslide/controls/) | Trả về bộ sưu tập các điều khiển ActiveX trên một slide.<br/>            Chỉ đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/notesslide/name/) | Trả về hoặc đặt tên của một slide.<br/>            Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/notesslide/slide_id/) | Trả về ID của một slide.<br/>            Chỉ đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/notesslide/custom_data/) | Trả về dữ liệu tùy chỉnh của slide.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/notesslide/timeline/) | Trả về đối tượng dòng thời gian hoạt ảnh.<br/>            Chỉ đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/notesslide/slide_show_transition/) | Trả về đối tượng Transition chứa thông tin về<br/>            cách slide đã chỉ định tiến triển trong một buổi chiếu slide.<br/>            Chỉ đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/notesslide/background/) | Trả về nền của slide.<br/>            Chỉ đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/notesslide/hyperlink_queries/) | Cung cấp truy cập dễ dàng tới các siêu liên kết được chứa.<br/>            Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/notesslide/show_master_shapes/) | Xác định xem các hình dạng trên master slide có nên được hiển thị trên các slide hay không.<br/>            Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/notesslide/presentation/) | Trả về giao diện IPresentation.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/notesslide/header_footer_manager/) | Trả về trình quản lý HeaderFooter của notes slide.<br/>            Chỉ đọc [`INotesSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/vi/aspose.slides/notesslide/notes_text_frame/) | Trả về một TextFrame chứa văn bản ghi chú nếu có.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/notesslide/theme_manager/) | Trả về trình quản lý theme ghi đè.<br/>            Chỉ đọc [`IOverrideThemeManager`](/slides/python-net/vi/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/vi/aspose.slides/notesslide/parent_slide/) | Trả về slide cha.<br/>            Chỉ đọc [`ISlide`](/slides/python-net/vi/aspose.slides/islide). |
| [`slide`](/slides/python-net/vi/aspose.slides/notesslide/slide/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Ghép các run có cùng định dạng trong tất cả các đoạn văn và các shape chấp nhận được. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Ghép các run có cùng định dạng trong tất cả các đoạn văn và các shape chấp nhận được. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/notesslide/equals/#ibaseslide) | Xác định xem hai đối tượng IBaseSlide có bằng nhau hay không.<br/>            Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh.<br/>            Hai slide bằng nhau nếu tất cả các shape, kiểu, văn bản, hoạt ảnh và các cài đặt khác, v.v. đều bằng nhau. So sánh không tính đến các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/notesslide/create_theme_effective/#) | Trả về theme hiệu quả cho slide này. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |

### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`NotesSlide`](/slides/python-net/vi/aspose.slides/notesslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)