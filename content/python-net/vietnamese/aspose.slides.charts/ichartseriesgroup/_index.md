---
title: IChartSeriesGroup class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup lớp

Đại diện cho nhóm các chuỗi.

Kiểu IChartSeriesGroup cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/type/) | Trả về kiểu của nhóm chuỗi này.<br/>            Chỉ-đọc [`CombinableSeriesTypesGroup`](/slides/python-net/vi/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Cho biết nếu chuỗi của nhóm này được vẽ trên trục phụ.<br/>            Chỉ-đọc **bool**. |
| [`series`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/series/) | Trả về một bộ sưu tập chỉ-đọc của các chuỗi biểu đồ.<br/>            Chỉ-đọc [`IChartSeriesReadonlyCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu.<br/>            Chỉ-đọc [`IUpDownBarsManager`](/slides/python-net/vi/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/gap_width/) | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính bằng phần trăm độ rộng của cột hoặc thanh.<br/>            Đọc/ghi **int**. |
| [`gap_depth`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng của dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D.<br/>            Đọc/ghi **int**. |
| [`first_slice_angle`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Lấy hoặc đặt góc của lát bánh tròn hoặc bánh vòng đầu tiên,<br/>            tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ).<br/>            Đọc/ghi **int**. |
| [`is_color_varied`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau.<br/>            Đọc/ghi **bool**. |
| [`has_series_lines`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ thanh xếp chồng và OfPie.<br/>            Đọc/ghi **bool**. |
| [`overlap`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/overlap/) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính theo phần trăm (từ -100% đến 100%).<br/>             - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời).<br/>             - 0%: Các thanh đặt cạnh nhau mà không chồng lấn hay cách nhau.<br/>             - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau).<br/>             Thuộc tính này là đọc/ghi **int**. |
| [`second_pie_size`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Xác định kích thước của bánh tròn thứ hai hoặc thanh của biểu đồ pie-of-pie hoặc <br/>            biểu đồ bar-of-pie, tính bằng phần trăm kích thước của bánh tròn đầu tiên (có thể <br/>            nằm trong khoảng 5 đến 200 phần trăm).<br/>            Đọc/ghi **int**. |
| [`pie_split_position`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh tròn thứ hai hoặc thanh trên biểu đồ pie-of-pie hoặc bar-of-pie.<br/>            Được sử dụng cùng với thuộc tính PieSplitBy.<br/>            Đọc/ghi **float**. |
| [`pie_split_by`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Xác định cách xác định các điểm dữ liệu nào nằm trong bánh tròn thứ hai hoặc thanh trên biểu đồ pie-of-pie hoặc bar-of-pie.<br/>            Đọc/ghi [`PieSplitType`](/slides/python-net/vi/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Thông tin chia phân tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có phân chia tùy chỉnh.<br/>            Chứa các điểm dữ liệu sẽ được vẽ trong bánh tròn thứ hai hoặc thanh trong một biểu đồ pie-of-pie hoặc <br/>            bar-of-pie.<br/>            Chỉ-đọc [`IPieSplitCustomPointCollection`](/slides/python-net/vi/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Xác định kích thước của lỗ trong biểu đồ doughnut (có thể nằm trong khoảng 10 đến 90 phần trăm kích thước của khu vực vẽ).<br/>            Đọc/ghi **int**. |
| [`bubble_size_scale`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Xác định hệ số tỉ lệ cho biểu đồ bubble (có thể nằm trong khoảng 0 đến 300 phần trăm kích thước mặc định).<br/>            Đọc/ghi **int**. |
| [`hi_low_lines_format`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Xác định định dạng HiLowLines. <br/>            HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble.<br/>            Đọc/ghi [`BubbleSizeRepresentationType`](/slides/python-net/vi/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Lấy phần tử tại chỉ mục được chỉ định.

## Bộ chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup.  
2) Nhóm chuỗi chứa một số thuộc tính chuỗi chung cho mỗi chuỗi trong nhóm ("series group properties").  
"Series group properties" trong lớp ChartSeriesGroup là đọc/ghi.  
Mỗi "series group properties" có thể có một dạng chiếu chỉ-đọc trong lớp ChartSeries.

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)