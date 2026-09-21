---
title: Chart class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chart/
---
## Lớp Chart

Đại diện cho một biểu đồ đồ họa trên một slide.

**Kế thừa:**[`Chart`](/slides/python-net/vi/aspose.slides.charts/chart) → [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/vi/aspose.slides/shape)

Kiểu Chart cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_text_holder`](/slides/python-net/vi/aspose.slides.charts/chart/is_text_holder/) | Xác định liệu shape có phải là TextHolder_PPT hay không.<br/>            Chỉ đọc **bool**. |
| [`placeholder`](/slides/python-net/vi/aspose.slides.charts/chart/placeholder/) | Trả về placeholder cho một shape. Trả về None nếu shape không có placeholder.<br/>            Chỉ đọc [`IPlaceholder`](/slides/python-net/vi/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/vi/aspose.slides.charts/chart/custom_data/) | Trả về dữ liệu tùy chỉnh của shape.<br/>            Chỉ đọc [`ICustomData`](/slides/python-net/vi/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/vi/aspose.slides.charts/chart/raw_frame/) | Trả về hoặc đặt các thuộc tính khung shape thô.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/vi/aspose.slides.charts/chart/frame/) | Trả về hoặc đặt các thuộc tính khung shape.<br/>            Đọc/ghi [`IShapeFrame`](/slides/python-net/vi/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/vi/aspose.slides.charts/chart/line_format/) | Trả về đối tượng LineFormat chứa các thuộc tính định dạng đường cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính đường.<br/>            Chỉ đọc [`ILineFormat`](/slides/python-net/vi/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/vi/aspose.slides.charts/chart/three_d_format/) | Trả về đối tượng ThreeDFormat chứa các thuộc tính hiệu ứng 3D cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính 3D.<br/>            Chỉ đọc [`IThreeDFormat`](/slides/python-net/vi/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/vi/aspose.slides.charts/chart/effect_format/) | Trả về đối tượng EffectFormat chứa các hiệu ứng pixel được áp dụng cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính hiệu ứng.<br/>            Chỉ đọc [`IEffectFormat`](/slides/python-net/vi/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/vi/aspose.slides.charts/chart/fill_format/) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho một shape.<br/>            Lưu ý: có thể trả về None đối với một số loại shape không có thuộc tính tô màu.<br/>            Chỉ đọc [`IFillFormat`](/slides/python-net/vi/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/vi/aspose.slides.charts/chart/hyperlink_click/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho nhấp chuột.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/vi/aspose.slides.charts/chart/hyperlink_mouse_over/) | Trả về hoặc đặt siêu liên kết được định nghĩa cho di chuột qua.<br/>            Đọc/ghi [`IHyperlink`](/slides/python-net/vi/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/vi/aspose.slides.charts/chart/hyperlink_manager/) | Trả về trình quản lý siêu liên kết.<br/>            Chỉ đọc [`IHyperlinkManager`](/slides/python-net/vi/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/vi/aspose.slides.charts/chart/hidden/) | Xác định liệu shape có bị ẩn hay không.<br/>            Đọc/ghi **bool**. |
| [`z_order_position`](/slides/python-net/vi/aspose.slides.charts/chart/z_order_position/) | Trả về vị trí của một shape trong thứ tự z.<br/>            Shapes[0] trả về shape ở phía sau cùng của thứ tự z,<br/>            và Shapes[Shapes.Count - 1] trả về shape ở phía trước cùng của thứ tự z.<br/>            Chỉ đọc **int**. |
| [`connection_site_count`](/slides/python-net/vi/aspose.slides.charts/chart/connection_site_count/) | Trả về số lượng điểm kết nối trên shape.<br/>            Chỉ đọc **int**. |
| [`rotation`](/slides/python-net/vi/aspose.slides.charts/chart/rotation/) | Trả về hoặc đặt số độ mà shape được xoay quanh trục z. Giá trị dương chỉ quay theo chiều kim đồng hồ; giá trị âm chỉ quay ngược chiều kim đồng hồ.<br/>            Đọc/ghi **float**. |
| [`x`](/slides/python-net/vi/aspose.slides.charts/chart/x/) | Lấy hoặc đặt tọa độ x của góc trên-trái của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides.charts/chart/y/) | Lấy hoặc đặt tọa độ y của góc trên-trái của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides.charts/chart/width/) | Lấy hoặc đặt chiều rộng của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides.charts/chart/height/) | Lấy hoặc đặt chiều cao của shape, đo bằng điểm.<br/>            Đọc/ghi **float**. |
| [`black_white_mode`](/slides/python-net/vi/aspose.slides.charts/chart/black_white_mode/) | Thuộc tính xác định cách shape sẽ hiển thị ở chế độ đen-trắng.<br/>            Đọc/ghi [`BlackWhiteMode`](/slides/python-net/vi/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/vi/aspose.slides.charts/chart/unique_id/) | Trả về một định danh nội bộ, phạm vi presentation, dành cho add-in hoặc mã khác.<br/>            Vì giá trị này có thể được người dùng hoặc chương trình thay đổi, nó không được coi là khóa duy nhất lâu dài.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.office_interop_shape_id`](/slides/python-net/vi/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/vi/aspose.slides.charts/chart/office_interop_shape_id/) | Trả về một định danh duy nhất có phạm vi slide, không thay đổi trong suốt vòng đời của shape và cho phép PowerPoint hoặc mã interop tham chiếu shape từ bất kỳ vị trí nào trong tài liệu.<br/>            Chỉ đọc **int**.<br/>            Xem thêm [`Shape.unique_id`](/slides/python-net/vi/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/vi/aspose.slides.charts/chart/alternative_text/) | Trả về hoặc đặt văn bản thay thế liên quan tới shape.<br/>            Đọc/ghi **str**. |
| [`alternative_text_title`](/slides/python-net/vi/aspose.slides.charts/chart/alternative_text_title/) | Trả về hoặc đặt tiêu đề của văn bản thay thế liên quan tới shape.<br/>            Đọc/ghi **str**. |
| [`name`](/slides/python-net/vi/aspose.slides.charts/chart/name/) | Trả về hoặc đặt tên của shape.<br/>            Không được để None. Nếu cần, sử dụng chuỗi rỗng.<br/>            Đọc/ghi **str**. |
| [`is_decorative`](/slides/python-net/vi/aspose.slides.charts/chart/is_decorative/) | Lấy hoặc đặt tùy chọn 'Đánh dấu là trang trí'<br/>            Đọc/ghi **bool**. |
| [`shape_lock`](/slides/python-net/vi/aspose.slides.charts/chart/shape_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/vi/aspose.slides.charts/chart/is_grouped/) | Xác định liệu shape có được nhóm hay không.<br/>            Chỉ đọc **bool**. |
| [`parent_group`](/slides/python-net/vi/aspose.slides.charts/chart/parent_group/) | Trả về đối tượng GroupShape cha nếu shape được nhóm. Nếu không, trả về None.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/chart/slide/) | Trả về slide cha của một shape.<br/>            Chỉ đọc [`IBaseSlide`](/slides/python-net/vi/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/chart/presentation/) | Trả về presentation cha của một slide.<br/>            Chỉ đọc [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/vi/aspose.slides.charts/chart/graphical_object_lock/) | Trả về các khóa của shape.<br/>            Chỉ đọc [`IGraphicalObjectLock`](/slides/python-net/vi/aspose.slides/igraphicalobjectlock). |
| [`plot_visible_cells_only`](/slides/python-net/vi/aspose.slides.charts/chart/plot_visible_cells_only/) | Xác định liệu chỉ các ô nhìn thấy được vẽ. Đặt False để vẽ cả ô nhìn thấy và ô ẩn.<br/>            Đọc/ghi **bool**. |
| [`display_blanks_as`](/slides/python-net/vi/aspose.slides.charts/chart/display_blanks_as/) | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ.<br/>            Đọc/ghi [`DisplayBlanksAsType`](/slides/python-net/vi/aspose.slides.charts/displayblanksastype). |
| [`chart_data`](/slides/python-net/vi/aspose.slides.charts/chart/chart_data/) | Trả về thông tin về dữ liệu liên kết hoặc nhúng liên quan tới biểu đồ.<br/>            Chỉ đọc [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata). |
| [`has_title`](/slides/python-net/vi/aspose.slides.charts/chart/has_title/) | Xác định liệu biểu đồ có tiêu đề hiển thị hay không.<br/>            Đọc/ghi **bool**. |
| [`chart_title`](/slides/python-net/vi/aspose.slides.charts/chart/chart_title/) | Trả về hoặc đặt tiêu đề biểu đồ.<br/>            Chỉ đọc [`IChartTitle`](/slides/python-net/vi/aspose.slides.charts/icharttitle). |
| [`has_data_table`](/slides/python-net/vi/aspose.slides.charts/chart/has_data_table/) | Xác định liệu biểu đồ có bảng dữ liệu hay không.<br/>            Đọc/ghi **bool**. |
| [`has_legend`](/slides/python-net/vi/aspose.slides.charts/chart/has_legend/) | Xác định liệu biểu đồ có chú giải hay không.<br/>            Đọc/ghi **bool**. |
| [`legend`](/slides/python-net/vi/aspose.slides.charts/chart/legend/) | Trả về hoặc đặt chú giải cho biểu đồ.<br/>            Chỉ đọc [`ILegend`](/slides/python-net/vi/aspose.slides.charts/ilegend). |
| [`chart_data_table`](/slides/python-net/vi/aspose.slides.charts/chart/chart_data_table/) | Trả về bảng dữ liệu của biểu đồ.<br/>            Chỉ đọc [`IDataTable`](/slides/python-net/vi/aspose.slides.charts/idatatable). |
| [`style`](/slides/python-net/vi/aspose.slides.charts/chart/style/) | Trả về hoặc đặt kiểu biểu đồ.<br/>            Đọc/ghi [`StyleType`](/slides/python-net/vi/aspose.slides.charts/styletype). |
| [`type`](/slides/python-net/vi/aspose.slides.charts/chart/type/) | Trả về hoặc đặt loại biểu đồ.<br/>            Đọc/ghi [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype). |
| [`plot_area`](/slides/python-net/vi/aspose.slides.charts/chart/plot_area/) | Đại diện cho khu vực vẽ của biểu đồ.<br/>            Chỉ đọc [`IChartPlotArea`](/slides/python-net/vi/aspose.slides.charts/ichartplotarea). |
| [`rotation_3d`](/slides/python-net/vi/aspose.slides.charts/chart/rotation_3d/) | Trả về phép xoay 3D của biểu đồ.<br/>            Chỉ đọc [`IRotation3D`](/slides/python-net/vi/aspose.slides.charts/irotation3d). |
| [`back_wall`](/slides/python-net/vi/aspose.slides.charts/chart/back_wall/) | Trả về đối tượng cho phép thay đổi định dạng của tường phía sau của biểu đồ 3D.<br/>            Chỉ đọc [`IChartWall`](/slides/python-net/vi/aspose.slides.charts/ichartwall). |
| [`side_wall`](/slides/python-net/vi/aspose.slides.charts/chart/side_wall/) | Trả về đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D.<br/>            Chỉ đọc [`IChartWall`](/slides/python-net/vi/aspose.slides.charts/ichartwall). |
| [`floor`](/slides/python-net/vi/aspose.slides.charts/chart/floor/) | Trả về đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D.<br/>            Chỉ đọc [`IChartWall`](/slides/python-net/vi/aspose.slides.charts/ichartwall). |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/chart/text_format/) | Trả về định dạng văn bản của biểu đồ.<br/>            Thuộc tính không áp dụng cho các kiểu sau: [`ChartType.TREEMAP`](/slides/python-net/vi/aspose.slides.charts/charttype/TREEMAP), [`ChartType.SUNBURST`](/slides/python-net/vi/aspose.slides.charts/charttype/SUNBURST),<br/>            [`ChartType.WATERFALL`](/slides/python-net/vi/aspose.slides.charts/charttype/WATERFALL), [`ChartType.HISTOGRAM`](/slides/python-net/vi/aspose.slides.charts/charttype/HISTOGRAM), [`ChartType.FUNNEL`](/slides/python-net/vi/aspose.slides.charts/charttype/FUNNEL),[`ChartType.BOX_AND_WHISKER`](/slides/python-net/vi/aspose.slides.charts/charttype/BOX_AND_WHISKER).<br/>            Chỉ đọc [`IChartTextFormat`](/slides/python-net/vi/aspose.slides.charts/icharttextformat). |
| [`theme_manager`](/slides/python-net/vi/aspose.slides.charts/chart/theme_manager/) | Trả về trình quản lý theme.<br/>            Chỉ đọc [`IOverrideThemeManager`](/slides/python-net/vi/aspose.slides.theme/ioverridethememanager). |
| [`user_shapes`](/slides/python-net/vi/aspose.slides.charts/chart/user_shapes/) | Chỉ định các shape được vẽ trên biểu đồ.<br/>            Chỉ đọc [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape). |
| [`axes`](/slides/python-net/vi/aspose.slides.charts/chart/axes/) | Cung cấp quyền truy cập vào các trục của biểu đồ.<br/>            Chỉ đọc [`IAxesManager`](/slides/python-net/vi/aspose.slides.charts/iaxesmanager). |
| [`show_data_labels_over_maximum`](/slides/python-net/vi/aspose.slides.charts/chart/show_data_labels_over_maximum/) | Xác định nhãn dữ liệu ở trên mức tối đa của biểu đồ sẽ được hiển thị.<br/>            Đọc/ghi **bool**. |
| [`has_rounded_corners`](/slides/python-net/vi/aspose.slides.charts/chart/has_rounded_corners/) | Xác định khu vực biểu đồ sẽ có góc tròn.<br/>            Đọc/ghi **bool**. |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/chart/chart/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_image(self)`](/slides/python-net/vi/aspose.slides.charts/chart/get_image/#) | Trả về ảnh thu nhỏ của shape.<br/>            Kiểu ShapeThumbnailBounds.Shape được sử dụng mặc định cho giới hạn ảnh thu nhỏ. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/vi/aspose.slides.charts/chart/get_image/#shapethumbnailbounds-float-float) | Trả về ảnh thu nhỏ của shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/vi/aspose.slides.charts/chart/write_as_svg/#iorawiobase) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/vi/aspose.slides.charts/chart/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Lưu nội dung của Shape dưới dạng tệp SVG. |
| [`remove_placeholder(self)`](/slides/python-net/vi/aspose.slides.charts/chart/remove_placeholder/#) | Xác định rằng shape này không phải là placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/vi/aspose.slides.charts/chart/add_placeholder/#iplaceholder) | Thêm một placeholder mới nếu không có và đặt các thuộc tính placeholder cho một placeholder cụ thể. |
| [`get_base_placeholder(self)`](/slides/python-net/vi/aspose.slides.charts/chart/get_base_placeholder/#) | Trả về một shape placeholder cơ bản (shape từ layout và/hoặc master slide mà shape hiện tại kế thừa).<br/>            Trả về None nếu shape hiện tại không kế thừa. |
| [`get_visual_bounds(self)`](/slides/python-net/vi/aspose.slides.charts/chart/get_visual_bounds/#) | Lấy giới hạn hình ảnh của shape được tính từ nội dung đã render. |
| [`validate_chart_layout(self)`](/slides/python-net/vi/aspose.slides.charts/chart/validate_chart_layout/#) | Tính toán các giá trị thực tế của các phần tử biểu đồ.<br/>            Các giá trị thực tế bao gồm vị trí của các phần tử thực hiện giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)<br/>            và các giá trị trục thực tế (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, <br/>            IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [`create_theme_effective(self)`](/slides/python-net/vi/aspose.slides.charts/chart/create_theme_effective/#) | Trả về theme hiệu quả cho biểu đồ này. |

### Xem thêm
* lớp [`Chart`](/slides/python-net/vi/aspose.slides.charts/chart)
* lớp [`GraphicalObject`](/slides/python-net/vi/aspose.slides/graphicalobject)
* lớp [`Shape`](/slides/python-net/vi/aspose.slides/shape)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)