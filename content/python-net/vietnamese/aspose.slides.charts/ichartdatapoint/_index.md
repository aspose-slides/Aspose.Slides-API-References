---
title: IChartDataPoint class
second_title: Tham khảo API Aspose.Slides for Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint lớp

Represents series data point.

The IChartDataPoint type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/x_value/) | Lấy giá trị x của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`IStringOrDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/y_value/) | Lấy giá trị y của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/bubble_size/) | Lấy kích thước bóng của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/value/) | Lấy giá trị của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Lấy giá trị X đã lưu của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`ICachedChartValue`](/slides/python-net/vi/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Lấy giá trị Y đã lưu của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`ICachedChartValue`](/slides/python-net/vi/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/cached_value/) | Lấy giá trị đã lưu của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`ICachedChartValue`](/slides/python-net/vi/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Lấy kích thước bóng đã lưu của một điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`ICachedChartValue`](/slides/python-net/vi/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/size_value/) | Lấy giá trị kích thước của một điểm dữ liệu biểu đồ.<br/>            Được sử dụng với biểu đồ Treemap và Sunburst. <br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/color_value/) | Lấy giá trị màu của một điểm dữ liệu biểu đồ.<br/>            Được sử dụng với biểu đồ Map. <br/>            Chỉ đọc [`IDoubleChartValue`](/slides/python-net/vi/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Đại diện cho giá trị thanh lỗi của chuỗi trong trường hợp kiểu giá trị Custom.<br/>            Chỉ đọc [`IErrorBarsCustomValues`](/slides/python-net/vi/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/label/) | Đại diện cho nhãn của điểm dữ liệu biểu đồ.<br/>            Chỉ đọc [`IDataLabel`](/slides/python-net/vi/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Xác định rằng các bong bóng có hiệu ứng 3-D được áp dụng.<br/>            Đọc/ghi **bool**. |
| [`explosion`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/explosion/) | Xác định lượng di chuyển của điểm dữ liệu khỏi trung tâm của bánh.<br/>            Đọc/ghi **int**. |
| [`format`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/format/) | Đại diện cho các thuộc tính định dạng.<br/>            Đọc/ghi [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/marker/) | Xác định một dấu dữ liệu.<br/>            Chỉ đọc [`IMarker`](/slides/python-net/vi/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách này:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Chỉ đọc [`ILegendEntryProperties`](/slides/python-net/vi/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/set_as_total/) | Đặt điểm dữ liệu làm tổng. Chỉ áp dụng cho loại chuỗi Waterfall. |
| [`invert_if_negative`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Xác định điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm.<br/>            Đọc/ghi **bool**. |
| [`data_point_levels`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Trả về container của các mức điểm dữ liệu. Áp dụng cho các chuỗi Treeamp và Sunburst.<br/>            Đánh chỉ mục mức điểm dữ liệu bắt đầu từ 0. |
| [`index`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/index/) | Xác định điểm dữ liệu này áp dụng cho bộ sưu tập con của cha nào.<br/>            Đọc **int**. |
| [`actual_x`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Phương thức

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/remove/#) | Xóa DataPoint khỏi chuỗi biểu đồ. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Trả về màu tự động của điểm dữ liệu dựa trên chỉ số chuỗi, chỉ số điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. <br/>            Màu này được sử dụng mặc định nếu FillType bằng NotDefined. |


### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)