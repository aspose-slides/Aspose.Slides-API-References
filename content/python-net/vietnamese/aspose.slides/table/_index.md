---
title: Table class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/table/
---
## Table lớp

Đại diện cho một bảng trên một slide.

**Kế thừa:**[`Table`](/slides/python-net/vi/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu Table cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides/table/is_text_holder/) | Xác định xem shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides/table/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides/table/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides/table/raw_frame/) | Trả về hoặc thiết lập các thuộc tính khung shape thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides/table/frame/) | Trả về hoặc thiết lập các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides/table/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides/table/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3d cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính 3d.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides/table/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho shape.<br/>            Lưu ý: có thể trả về None cho một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides/table/fill_format/) | Trả về đối tượng TableFormat.FillFormat chứa định dạng tô màu cho Table.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides/table/hyperlink_click/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho click chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides/table/hyperlink_mouse_over/) | Trả về hoặc thiết lập hyperlink được định nghĩa cho hover chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides/table/hyperlink_manager/) | Trả về quản lý hyperlink.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides/table/hidden/) | Xác định xem shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides/table/z_order_position/) | Trả về vị trí của shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở phía sau trong thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước trong thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides/table/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides/table/rotation/) | Trả về hoặc thiết lập số độ mà shape được xoay quanh trục z.<br/>            Giá trị dương cho biết xoay theo chiều kim đồng hồ; giá trị âm cho biết xoay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides/table/x/) | Lấy hoặc thiết lập tọa độ x của góc trên-trái của shape, đo bằng point.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides/table/y/) | Lấy hoặc thiết lập tọa độ y của góc trên-trái của shape, đo bằng point.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides/table/width/) | Lấy hoặc thiết lập độ rộng của shape, đo bằng point.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides/table/height/) | Lấy hoặc thiết lập chiều cao của shape, đo bằng point.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides/table/black_white_mode/) | Thuộc tính chỉ định cách shape sẽ được hiển thị ở chế độ hiển thị đen-trắng..<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides/table/unique_id/) | Trả về một định danh nội bộ, phạm vi bản trình bày, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, không nên coi nó là khóa duy nhất kéo dài.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides/table/office_interop_shape_id/) | Trả về một định danh duy nhất phạm vi slide, không thay đổi trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape một cách đáng tin cậy từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides/table/alternative_text/) | Trả về hoặc thiết lập văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides/table/alternative_text_title/) | Trả về hoặc thiết lập tiêu đề của văn bản thay thế liên quan đến shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides/table/name/) | Trả về hoặc thiết lập tên của shape.<br/>            Phải không phải None. Dùng chuỗi rỗng nếu cần.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides/table/is_decorative/) | Lấy hoặc thiết lập tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides/table/shape_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides/table/is_grouped/) | Xác định xem shape có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides/table/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides/table/slide/) | Trả về slide cha của shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides/table/presentation/) | Trả về bản trình bày cha của slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides/table/graphical_object_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/vi/aspose.slides/table/rows/) | Trả về tập hợp các hàng.<br/>            Chỉ đọc [`IRowCollection`](/slides/python-net/vi/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/vi/aspose.slides/table/columns/) | Trả về tập hợp các cột.<br/>            Chỉ đọc [`IColumnCollection`](/slides/python-net/vi/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/vi/aspose.slides/table/table_format/) | Trả về đối tượng TableFormat chứa các thuộc tính định dạng cho bảng này.<br/>            Chỉ đọc [`ITableFormat`](/slides/python-net/vi/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/vi/aspose.slides/table/style_preset/) | Lấy hoặc thiết lập kiểu bảng tích hợp.<br/>            Đọc/ghi [`TableStylePreset`](/slides/python-net/vi/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/vi/aspose.slides/table/right_to_left/) | Xác định xem bảng có thứ tự đọc từ phải sang trái hay không.<br/>            Đọc/ghi **bool**. |
| [`first_row`](/slides/python-net/vi/aspose.slides/table/first_row/) | Xác định xem hàng đầu tiên của bảng có được vẽ với định dạng đặc biệt hay không.<br/>            Đọc/ghi **bool**. |
| [`first_col`](/slides/python-net/vi/aspose.slides/table/first_col/) | Xác định xem cột đầu tiên của bảng có được vẽ với định dạng đặc biệt hay không.<br/>            Đọc/ghi **bool**. |
| [`last_row`](/slides/python-net/vi/aspose.slides/table/last_row/) | Xác định xem hàng cuối cùng của bảng có được vẽ với định dạng đặc biệt hay không.<br/>            Đọc/ghi **bool**. |
| [`last_col`](/slides/python-net/vi/aspose.slides/table/last_col/) | Xác định xem cột cuối cùng của bảng có được vẽ với định dạng đặc biệt hay không.<br/>            Đọc/ghi **bool**. |
| [`horizontal_banding`](/slides/python-net/vi/aspose.slides/table/horizontal_banding/) | Xác định xem các hàng chẵn có được vẽ với định dạng khác không.<br/>            Đọc/ghi **bool**. |
| [`vertical_banding`](/slides/python-net/vi/aspose.slides/table/vertical_banding/) | Xác định xem các cột chẵn có được vẽ với định dạng khác không.<br/>            Đọc/ghi **bool**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides/table/get_image/#) | Trả về thumbnail của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng làm mặc định cho giới hạn thumbnail. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | Trả về thumbnail của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides/table/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`set_text_format(self, source)`](/slides/python-net/vi/aspose.slides/table/set_text_format/#iportionformat) | Thiết lập các thuộc tính định dạng phần đã định nghĩa cho tất cả các phần của các ô trong bảng. |
| [`set_text_format(self, source)`](/slides/python-net/vi/aspose.slides/table/set_text_format/#iparagraphformat) | Thiết lập các thuộc tính định dạng đoạn văn đã định nghĩa cho tất cả các đoạn văn của các ô trong bảng. |
| [`set_text_format(self, source)`](/slides/python-net/vi/aspose.slides/table/set_text_format/#itextframeformat) | Thiết lập các thuộc tính định dạng khung văn bản đã định nghĩa cho tất cả các khung văn bản của các ô trong bảng. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides/table/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides/table/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và thiết lập các thuộc tính placeholder cho một placeholder được chỉ định. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides/table/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại được kế thừa).<br/>            Trả về None nếu shape hiện tại không được kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides/table/get_visual_bounds/#) | Lấy giới hạn hình ảnh của shape được tính từ nội dung đã render. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/vi/aspose.slides/table/merge_cells/#icell-icell-bool) | Hợp nhất các ô liền kề. |

### Xem Thêm
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* lớp [`Table`](/slides/python-net/vi/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)