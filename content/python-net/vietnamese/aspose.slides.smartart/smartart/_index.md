---
title: SmartArt class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.smartart/smartart/
---
## Lớp SmartArt

Biểu diễn một sơ đồ SmartArt

**Kế thừa:**[`SmartArt`](/slides/python-net/vi/aspose.slides.smartart/smartart) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu SmartArt cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides.smartart/smartart/is_text_holder/) | Xác định xem hình dạng có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides.smartart/smartart/placeholder/) | Trả về phần giữ chỗ cho một hình dạng. Trả về None nếu hình dạng không có phần giữ chỗ.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides.smartart/smartart/custom_data/) | Trả về dữ liệu tùy chỉnh của hình dạng.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides.smartart/smartart/raw_frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng thô.<br/>            Đọc/Ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides.smartart/smartart/frame/) | Trả về hoặc đặt các thuộc tính khung hình dạng.<br/>            Đọc/Ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides.smartart/smartart/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một hình dạng.<br/>            Lưu ý: có thể trả về None đối với một số loại hình dạng không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides.smartart/smartart/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một hình dạng.<br/>            Lưu ý: có thể trả về None đối với một số loại hình dạng không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides.smartart/smartart/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một hình dạng.<br/>            Lưu ý: có thể trả về None đối với một số loại hình dạng không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides.smartart/smartart/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một hình dạng.<br/>            Lưu ý: có thể trả về None đối với một số loại hình dạng không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides.smartart/smartart/hyperlink_click/) | Trả về hoặc đặt siêu liên kết định nghĩa cho cú nhấp chuột.<br/>            Đọc/Ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides.smartart/smartart/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết định nghĩa cho di chuột.<br/>            Đọc/Ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides.smartart/smartart/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides.smartart/smartart/hidden/) | Xác định xem hình dạng có bị ẩn hay không.<br/>            Đọc/Ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides.smartart/smartart/z_order_position/) | Trả về vị trí của một hình dạng trong thứ tự z.<br/>            Shapes[0] trả về hình dạng ở phía sau của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về hình dạng ở phía trước của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides.smartart/smartart/connection_site_count/) | Trả về số lượng điểm kết nối trên hình dạng.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides.smartart/smartart/rotation/) | Trả về hoặc đặt số độ mà hình dạng được quay quanh trục z.<br/>            Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/Ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides.smartart/smartart/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/Ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides.smartart/smartart/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của hình dạng, đo bằng điểm.<br/>            Đọc/Ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides.smartart/smartart/width/) | Lấy hoặc đặt chiều rộng của hình dạng, đo bằng điểm.<br/>            Đọc/Ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides.smartart/smartart/height/) | Lấy hoặc đặt chiều cao của hình dạng, đo bằng điểm.<br/>            Đọc/Ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides.smartart/smartart/black_white_mode/) | Thuộc tính chỉ định cách một hình dạng sẽ hiển thị trong chế độ đen-trắng.<br/>            Đọc/Ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides.smartart/smartart/unique_id/) | Trả về một định danh nội bộ, có phạm vi trong bản trình chiếu, dành cho các add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi nó như một khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides.smartart/smartart/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi trong slide, không thay đổi trong suốt vòng đời của hình dạng và<br/>            cho phép PowerPoint hoặc mã interop tham chiếu hình dạng một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides.smartart/smartart/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan tới một hình dạng.<br/>            Đọc/Ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides.smartart/smartart/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan tới một hình dạng.<br/>            Đọc/Ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides.smartart/smartart/name/) | Trả về hoặc đặt tên của một hình dạng.<br/>            Không được để là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/Ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides.smartart/smartart/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/Ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides.smartart/smartart/shape_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides.smartart/smartart/is_grouped/) | Xác định xem hình dạng có được nhóm không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides.smartart/smartart/parent_group/) | Trả về đối tượng GroupShape cha nếu hình dạng được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides.smartart/smartart/slide/) | Trả về slide cha của một hình dạng.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides.smartart/smartart/presentation/) | Trả về bản trình chiếu cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides.smartart/smartart/graphical_object_lock/) | Trả về các khóa của hình dạng.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`all_nodes`](/slides/python-net/vi/aspose.slides.smartart/smartart/all_nodes/) | Trả về tập hợp các nút trong đối tượng SmartArt.<br/>            Chỉ đọc [`ISmartArtNodeCollection`](/slides/python-net/vi/aspose.slides.smartart/ismartartnodecollection). |
| [`nodes`](/slides/python-net/vi/aspose.slides.smartart/smartart/nodes/) | Trả về tập hợp các nút gốc trong đối tượng SmartArt.<br/>            Chỉ đọc [`ISmartArtNodeCollection`](/slides/python-net/vi/aspose.slides.smartart/ismartartnodecollection). |
| [`layout`](/slides/python-net/vi/aspose.slides.smartart/smartart/layout/) | Trả về hoặc đặt bố cục của đối tượng SmartArt.<br/>            Đọc/Ghi [`SmartArtLayoutType`](/slides/python-net/vi/aspose.slides.smartart/smartartlayouttype). |
| [`quick_style`](/slides/python-net/vi/aspose.slides.smartart/smartart/quick_style/) | Trả về hoặc đặt kiểu nhanh của đối tượng SmartArt.<br/>            Đọc/Ghi [`SmartArtQuickStyleType`](/slides/python-net/vi/aspose.slides.smartart/smartartquickstyletype). |
| [`color_style`](/slides/python-net/vi/aspose.slides.smartart/smartart/color_style/) | Trả về hoặc đặt kiểu màu của đối tượng SmartArt.<br/>            Đọc/Ghi [`SmartArtColorType`](/slides/python-net/vi/aspose.slides.smartart/smartartcolortype). |
| [`is_reversed`](/slides/python-net/vi/aspose.slides.smartart/smartart/is_reversed/) | Trả về hoặc đặt trạng thái của sơ đồ SmartArt liên quan tới (trái-sang-phải) LTR hoặc (phải-sang-trái) RTL, nếu sơ đồ hỗ trợ đảo ngược.<br/>            Đọc/Ghi **bool**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides.smartart/smartart/get_image/#) | Trả về hình thu nhỏ của hình dạng.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn hình thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides.smartart/smartart/get_image/#shapethumbnailbounds-float-float) | Trả về hình thu nhỏ của hình dạng. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides.smartart/smartart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides.smartart/smartart/remove_placeholder/#) | Xác định rằng hình dạng này không phải là phần giữ chỗ. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides.smartart/smartart/add_placeholder/#iplaceholder) | Thêm một phần giữ chỗ mới nếu không có và đặt các thuộc tính phần giữ chỗ thành một phần giữ chỗ được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides.smartart/smartart/get_base_placeholder/#) | Trả về một hình dạng phần giữ chỗ cơ bản (hình dạng từ bố cục và/hoặc slide mẫu mà hình dạng hiện tại kế thừa).<br/>            Trả về None nếu hình dạng hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides.smartart/smartart/get_visual_bounds/#) | Lấy giới hạn hình ảnh của hình dạng được tính toán từ nội dung đã hiển thị. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`SmartArt`](/slides/python-net/vi/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/vi/aspose.slides.smartart)
* thư viện [`Aspose.Slides`](/slides/python-net)