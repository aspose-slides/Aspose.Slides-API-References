---
title: Ink class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.ink/ink/
---
## Lớp Ink

Đại diện cho một đối tượng mực trên slide.

**Kế thừa:**[`Ink`](/slides/python-net/vi/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu Ink cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides.ink/ink/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides.ink/ink/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides.ink/ink/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides.ink/ink/raw_frame/) | Trả về hoặc đặt các thuộc tính khung shape thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides.ink/ink/frame/) | Trả về hoặc đặt các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides.ink/ink/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides.ink/ink/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides.ink/ink/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel áp dụng cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides.ink/ink/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides.ink/ink/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho click chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides.ink/ink/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides.ink/ink/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides.ink/ink/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides.ink/ink/z_order_position/) | Trả về vị trí của shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides.ink/ink/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides.ink/ink/rotation/) | Trả về hoặc đặt số độ mà shape được quay quanh trục z.<br/>            Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides.ink/ink/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides.ink/ink/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides.ink/ink/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides.ink/ink/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides.ink/ink/black_white_mode/) | Thuộc tính chỉ định cách shape sẽ hiển thị trong chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides.ink/ink/unique_id/) | Trả về một định danh nội bộ, thuộc phạm vi bài thuyết trình, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình gán lại, không nên coi như một khóa duy nhất bền vững.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides.ink/ink/office_interop_shape_id/) | Trả về một định danh duy nhất thuộc phạm vi slide, không thay đổi trong suốt thời gian tồn tại của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides.ink/ink/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides.ink/ink/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides.ink/ink/name/) | Trả về hoặc đặt tên của shape.<br/>            Không được để là None. Sử dụng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides.ink/ink/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides.ink/ink/shape_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides.ink/ink/is_grouped/) | Xác định xem shape có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides.ink/ink/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides.ink/ink/slide/) | Trả về slide cha của shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides.ink/ink/presentation/) | Trả về bản thuyết trình cha của slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides.ink/ink/graphical_object_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/vi/aspose.slides.ink/ink/traces/) | Lấy tất cả các trace chứa trong phần tử IInk [`IInkTrace`](/slides/python-net/vi/aspose.slides.ink/iinktrace).<br/>            Chỉ đọc. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides.ink/ink/get_image/#) | Trả về ảnh thu nhỏ của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho giới hạn ảnh thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides.ink/ink/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides.ink/ink/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ bố cục và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides.ink/ink/get_visual_bounds/#) | Lấy giới hạn trực quan của shape được tính từ nội dung đã render. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/vi/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | Đăng ký một hình ảnh vào bộ sưu tập các hình ảnh tùy chỉnh dùng để mô phỏng hiệu ứng visual cho bút mực.<br/>            Những hình ảnh này được dùng khi render mực với các giá trị [`InkEffectType`](/slides/python-net/vi/aspose.slides.ink/inkeffecttype) cụ thể,<br/>            như Galaxy, Rainbow, v.v. Bằng cách cung cấp hình ảnh của riêng bạn, bạn có thể kiểm soát cách mỗi hiệu ứng mực xuất hiện. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/vi/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | Hủy đăng ký một hình ảnh khỏi bộ sưu tập các hình ảnh tùy chỉnh dùng để mô phỏng hiệu ứng visual cho bút mực<br/>            đã đăng ký trước đó thông qua **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### Xem thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Ink`](/slides/python-net/vi/aspose.slides.ink/ink)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* module [`aspose.slides.ink`](/slides/python-net/vi/aspose.slides.ink)
* thư viện [`Aspose.Slides`](/slides/python-net)