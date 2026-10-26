---
title: BaseSlide class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/baseslide/
---
## Lớp BaseSlide

Mô tả dữ liệu chung cho tất cả các loại slide.

Kiểu BaseSlide cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/vi/aspose.slides/baseslide/shapes/) | Trả về các shape của một slide.<br/> Chỉ đọc [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/vi/aspose.slides/baseslide/controls/) | Trả về bộ sưu tập các điều khiển ActiveX trên một slide.<br/> Chỉ đọc [`IControlCollection`](/slides/python-net/vi/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/vi/aspose.slides/baseslide/name/) | Trả về hoặc đặt tên của một slide.<br/> Đọc/ghi **str**. |
| [`slide_id`](/slides/python-net/vi/aspose.slides/baseslide/slide_id/) | Trả về ID của một slide.<br/> Chỉ đọc **int**. |
| [`custom_data`](/slides/python-net/vi/aspose.slides/baseslide/custom_data/) | Trả về dữ liệu tùy chỉnh của slide.<br/> Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/vi/aspose.slides/baseslide/timeline/) | Trả về đối tượng timeline hoạt hình.<br/> Chỉ đọc [`IAnimationTimeLine`](/slides/python-net/vi/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/vi/aspose.slides/baseslide/slide_show_transition/) | Trả về đối tượng Transition chứa thông tin về cách slide được chỉ định tiến trình trong buổi chiếu slide.<br/> Chỉ đọc [`ISlideShowTransition`](/slides/python-net/vi/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/vi/aspose.slides/baseslide/background/) | Trả về nền của slide.<br/> Chỉ đọc [`IBackground`](/slides/python-net/vi/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/vi/aspose.slides/baseslide/hyperlink_queries/) | Cung cấp truy cập dễ dàng tới các siêu liên kết có trong.<br/> Chỉ đọc [`IHyperlinkQueries`](/slides/python-net/vi/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/vi/aspose.slides/baseslide/show_master_shapes/) | Xác định xem các shape trên master slide có nên hiển thị trên các slide hay không.<br/> Đối với master slide tự nó, thuộc tính này luôn trả về `false`.<br/> Đọc/ghi **bool**. |
| [`presentation`](/slides/python-net/vi/aspose.slides/baseslide/presentation/) | Trả về giao diện IPresentation.<br/> Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/vi/aspose.slides/baseslide/slide/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/vi/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Kết hợp các run có cùng định dạng trong tất cả các đoạn văn và tất cả các shape cho phép. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/vi/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Kết hợp các run có cùng định dạng trong tất cả các đoạn văn trong tất cả các shape cho phép. |
| [`equals(self, slide)`](/slides/python-net/vi/aspose.slides/baseslide/equals/#ibaseslide) | Xác định xem hai thể hiện IBaseSlide có bằng nhau hay không.<br/> Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh.<br/> Hai slide được coi bằng nhau nếu tất cả các shape, style, văn bản, hoạt hình và các thiết lập khác, v.v. đều bằng nhau. So sánh không xem xét các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides/baseslide/create_theme_effective/#) | Trả về một theme hiệu quả cho slide này. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/vi/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)