---
title: LegacyDiagram class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/legacydiagram/
---
## LegacyDiagram lớp

Represents a legacy diagram object.

**Inheritance:**[`LegacyDiagram`](/slides/python-net/vi/aspose.slides/legacydiagram) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

The LegacyDiagram type exposes the following members:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/legacydiagram/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/legacydiagram/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/legacydiagram/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/legacydiagram/raw_frame/) | Trả về hoặc đặt các thuộc tính khung shape thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/legacydiagram/frame/) | Trả về hoặc đặt các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/legacydiagram/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/legacydiagram/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho một shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/legacydiagram/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho một shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/legacydiagram/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng fill cho một shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính fill.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/legacydiagram/hyperlink_click/) | Trả về hoặc đặt hyperlink được định nghĩa cho mouse click.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/legacydiagram/hyperlink_mouse_over/) | Trả về hoặc đặt hyperlink được định nghĩa cho mouse over.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/legacydiagram/hyperlink_manager/) | Trả về hyperlink manager.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/legacydiagram/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/legacydiagram/z_order_position/) | Trả về vị trí của một shape trong z-order.<br/>            Shapes[0] trả về shape ở phía sau của z-order,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước của z-order.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/legacydiagram/connection_site_count/) | Trả về số connection sites trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/legacydiagram/rotation/) | Trả về hoặc đặt số độ shape được xoay quanh trục z.<br/>            Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/legacydiagram/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng points.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/legacydiagram/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng points.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/legacydiagram/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng points.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/legacydiagram/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng points.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/legacydiagram/black_white_mode/) | Thuộc tính chỉ định cách một shape sẽ render trong chế độ hiển thị đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/legacydiagram/unique_id/) | Trả về một identifier nội bộ, phạm vi presentation, dành cho add-ins hoặc code khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, nên không được coi là khóa duy nhất cố định.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/legacydiagram/office_interop_shape_id/) | Trả về một identifier duy nhất phạm vi slide, không thay đổi trong suốt vòng đời của shape và cho phép PowerPoint hoặc code interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/legacydiagram/alternative_text/) | Trả về hoặc đặt alternative text liên quan tới một shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/legacydiagram/alternative_text_title/) | Trả về hoặc đặt tiêu đề của alternative text liên quan tới một shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/legacydiagram/name/) | Trả về hoặc đặt tên của một shape.<br/>            Không được để None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/legacydiagram/is_decorative/) | Lấy hoặc đặt tùy chọn 'Mark as decorative'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/legacydiagram/shape_lock/) | Trả về các locks của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/legacydiagram/is_grouped/) | Xác định xem shape có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/legacydiagram/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/legacydiagram/slide/) | Trả về slide cha của một shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/legacydiagram/presentation/) | Trả về presentation cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/legacydiagram/graphical_object_lock/) | Trả về các locks của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/get_image/#) | Trả về shape thumbnail.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho bounds thumbnail. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/legacydiagram/get_image/#shapethumbnailbounds-float-float) | Trả về shape thumbnail. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/legacydiagram/write_as_svg/#iorawiobase) | Lưu nội dung của Shape thành tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/legacydiagram/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape thành tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/remove_placeholder/#) | Xác định rằng shape này không phải là một placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/legacydiagram/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/get_visual_bounds/#) | Lấy visual bounds của shape được tính từ nội dung đã render. |
| [`convert_to_smart_art(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/convert_to_smart_art/#) | Chuyển đổi legacy digram thành đối tượng SmartArt có thể chỉnh sửa.<br/>            Đối tượng SmartArt được tạo sẽ được thêm vào parent group shape ở cùng vị trí. |
| [`convert_to_group_shape(self)`](/slides/python-net/vi/aspose.slides/legacydiagram/convert_to_group_shape/#) | Chuyển đổi legacy digram thành group shape có thể chỉnh sửa.<br/>            Đối tượng GroupShape được tạo sẽ được thêm vào parent group shape ở cùng vị trí. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`LegacyDiagram`](/slides/python-net/vi/aspose.slides/legacydiagram)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)