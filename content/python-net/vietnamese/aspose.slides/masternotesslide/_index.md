---
title: MasterNotesSlide class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/masternotesslide/
---
## Lớp MasterNotesSlide

Đại diện cho slide chủ cho ghi chú.

**Kế thừa:**[`MasterNotesSlide`](/slides/python-net/vi/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)

Kiểu MasterNotesSlide cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/masternotesslide/shapes/) | Trả về các hình dạng của một slide.<br/>            Read-only [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/masternotesslide/controls/) | Trả về tập hợp các điều khiển ActiveX trên một slide.<br/>            Read-only [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/masternotesslide/name/) | Trả về hoặc đặt tên của một slide.<br/>            Read/write **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/masternotesslide/slide_id/) | Trả về ID của một slide.<br/>            Read-only **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/masternotesslide/custom_data/) | Trả về dữ liệu tùy chỉnh của slide.<br/>            Read-only [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/masternotesslide/timeline/) | Trả về đối tượng dòng thời gian hoạt hình.<br/>            Read-only [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/masternotesslide/slide_show_transition/) | Trả về đối tượng Transition chứa thông tin về<br/>            cách slide được chỉ định tiến hành trong buổi chiếu slide.<br/>            Read-only [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/masternotesslide/background/) | Trả về nền của slide.<br/>            Read-only [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/masternotesslide/hyperlink_queries/) | Cung cấp truy cập dễ dàng tới các hyperlink có trong.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/masternotesslide/show_master_shapes/) | Xác định liệu các hình dạng trên master slide có nên hiển thị trên các slide hay không.<br/>            Đối với master slide bản thân, thuộc tính này luôn trả về `false`.<br/>            Read/write **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/masternotesslide/presentation/) | Trả về giao diện IPresentation.<br/>            Read-only [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/vi/aspose.slides/masternotesslide/header_footer_manager/) | Trả về trình quản lý HeaderFooter của master notes slide.<br/>            Read-only [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/vi/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides/masternotesslide/theme_manager/) | Trả về trình quản lý theme.<br/>            Read-only [`IMasterThemeManager`](/slides/python-net/vi/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/vi/aspose.slides/masternotesslide/notes_style/) | Trả về kiểu chữ của văn bản ghi chú.<br/>            Read-only [`ITextStyle`](/slides/python-net/vi/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/vi/aspose.slides/masternotesslide/drawing_guides/) | Trả về một tập hợp các hướng dẫn vẽ cho master notes slide.<br/>            Read-only [`IDrawingGuidesCollection`](/slides/python-net/vi/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/vi/aspose.slides/masternotesslide/slide/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Gộp các run có cùng định dạng trong tất cả các đoạn văn và mọi hình dạng chấp nhận được. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Gộp các run có cùng định dạng trong tất cả các đoạn văn trong mọi hình dạng chấp nhận được. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/masternotesslide/equals/#ibaseslide) | Xác định xem hai thể hiện IBaseSlide có bằng nhau không.<br/>            Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide.<br/>            Hai slide bằng nhau nếu tất cả các hình dạng, kiểu, văn bản, hoạt hình và các cài đặt khác, v.t. đều bằng nhau. So sánh không xem xét các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/masternotesslide/create_theme_effective/#) | Trả về theme hiệu quả cho slide này. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Tìm vị trí đầu tiên của một hình dạng có văn bản thay thế được chỉ định. |


### Xem thêm
* lớp [`BaseSlide`](/slides/python-net/vi/aspose.slides/baseslide)
* lớp [`MasterNotesSlide`](/slides/python-net/vi/aspose.slides/masternotesslide)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)