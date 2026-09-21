---
title: ChartDataPoint class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint lớp

Biểu diễn điểm dữ liệu của series.

Kiểu ChartDataPoint mở ra các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Chỉ đọc [`IStringOrDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/size_value/) | Trả về giá trị kích thước của điểm dữ liệu biểu đồ.<br/>            Được sử dụng với biểu đồ Treemap và Sunburst.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/color_value/) | Trả về giá trị màu của điểm dữ liệu biểu đồ.<br/>            Được sử dụng với biểu đồ Map.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Biểu diễn các giá trị thanh lỗi của series trong trường hợp kiểu giá trị Custom.<br/>            Chỉ đọc [`IErrorBarsCustomValues`](/slides/python-net/vi/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Chỉ đọc [`IDataLabel`](/slides/python-net/vi/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Xác định rằng các bubbles có hiệu ứng 3-D được áp dụng.<br/>            Đọc/ghi **bool**. |
| [`explosion`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/explosion/) | Xác định khoảng cách mà điểm dữ liệu sẽ được di chuyển ra khỏi trung tâm của biểu đồ tròn.<br/>            Đọc/ghi **int**. |
| [`format`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/format/) | Biểu diễn các thuộc tính định dạng.<br/>            Đọc/ghi [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/marker/) | Xác định một dấu dữ liệu.<br/>            Chỉ đọc [`IMarker`](/slides/python-net/vi/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/set_as_total/) | Đặt điểm dữ liệu làm tổng. Chỉ áp dụng cho loại series Waterfall. |
| [`related_legend_entry`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách sau:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Chỉ đọc [`ILegendEntryProperties`](/slides/python-net/vi/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/data_point_levels/) | Trả về container của các cấp độ điểm dữ liệu. Được áp dụng cho series Treeamp và Sunburst.<br/>            Chỉ mục các cấp độ điểm dữ liệu bắt đầu từ 0. |
| [`index`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Xác định rằng điểm dữ liệu sẽ đảo màu nếu giá trị âm.<br/>            Đọc/ghi **bool**. |
| [`actual_x`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/actual_x/) | Xác định vị trí x thực tế (trái) của thành phần biểu đồ so với góc trên bên trái của biểu đồ.<br/>            Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_y`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/actual_y/) | Xác định vị trí trên thực tế của thành phần biểu đồ so với góc trên bên trái của biểu đồ.<br/>            Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_width`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/actual_width/) | Xác định chiều rộng thực tế của thành phần biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_height`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/actual_height/) | Xác định chiều cao thực tế của thành phần biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/remove/#) | Xóa DataPoint khỏi series biểu đồ. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/vi/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Trả về màu tự động của điểm dữ liệu dựa trên chỉ mục series, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ.<br/>            Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)