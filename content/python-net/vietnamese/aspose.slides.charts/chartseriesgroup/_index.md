---
title: ChartSeriesGroup class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup lớp

Biểu diễn một nhóm series.

Kiểu ChartSeriesGroup cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/type/) | Trả về kiểu của nhóm series này.<br/>            Chỉ đọc [`CombinableSeriesTypesGroup`](/slides/python-net/vi/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Cho biết series của nhóm này có được vẽ trên trục phụ hay không.<br/>            Chỉ đọc **bool**. |
| [`series`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/series/) | Trả về một tập hợp các series.<br/>            Chỉ đọc [`IChartSeriesReadonlyCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Cung cấp quyền truy cập vào thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu.<br/>            Chỉ đọc [`IUpDownBarsManager`](/slides/python-net/vi/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/gap_width/) | Xác định khoảng cách giữa các cụm cột hoặc thanh, tính theo phần trăm độ rộng của cột hoặc thanh.<br/>            Đọc/ghi **int**. |
| [`gap_depth`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/gap_depth/) | Trả về hoặc đặt khoảng cách, tính theo phần trăm độ rộng của marker, giữa các series dữ liệu trong biểu đồ 3D.<br/>            Đọc/ghi **int**. |
| [`first_slice_angle`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Lấy hoặc đặt góc của lát bánh pie hoặc donut đầu tiên, <br/>            tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ).<br/>            Đọc/ghi **int**. |
| [`doughnut_hole_size`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Xác định kích thước của lỗ trong biểu đồ donut (có thể từ 0 tới 90% <br/>            của kích thước vùng vẽ).<br/>            Đọc/ghi **int**. |
| [`overlap`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/overlap/) | Xác định mức độ chồng lấp của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%).<br/>             - -100%: Khoảng cách tối đa (các thanh được tách hoàn toàn).<br/>             - 0%: Các thanh được đặt cạnh nhau mà không chồng lấp hoặc có khoảng cách.<br/>             - 100%: Chồng lấp tối đa (các thanh hoàn toàn chồng lên nhau).<br/>             Thuộc tính này là đọc/ghi **int**. |
| [`second_pie_size`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Xác định kích thước của phần bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh đầu tiên (có thể <br/>            từ 5 tới 200%).<br/>            Đọc/ghi **int**. |
| [`bubble_size_representation`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Xác định cách các giá trị kích thước bong bóng được hiển thị trên biểu đồ bong bóng.<br/>            Đọc/ghi [`BubbleSizeRepresentationType`](/slides/python-net/vi/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Xác định giá trị sẽ được sử dụng để quyết định các điểm dữ liệu <br/>            nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. <br/>            Được sử dụng cùng với thuộc tính PieSplitBy.<br/>            Đọc/ghi **float**. |
| [`pie_split_by`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Xác định cách quyết định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai <br/>            trên biểu đồ pie-of-pie hoặc bar-of-pie.<br/>            Đọc/ghi [`PieSplitType`](/slides/python-net/vi/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Xác định rằng mỗi dấu dữ liệu trong series có màu khác nhau.<br/>            Đọc/ghi **bool**. |
| [`has_series_lines`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Đúng nếu biểu đồ có các đường series. Áp dụng cho biểu đồ stacked bar và OfPie.<br/>            Đọc/ghi **bool**. |
| [`hi_low_lines_format`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Xác định định dạng HiLowLines. <br/>            HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể <br/>            từ 0 tới 300% kích thước mặc định).<br/>            Đọc/ghi **int**. |
| [`pie_split_custom_points`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Thông tin phân chia tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có phân chia tùy chỉnh.<br/>            Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc <br/>            bar-of-pie.<br/>            Chỉ đọc [`PieSplitCustomPointCollection`](/slides/python-net/vi/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/chart/) | Trả về biểu đồ cha.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Lấy phần tử tại chỉ mục được chỉ định.

## Chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup.  
2) Nhóm series chứa một số thuộc tính series mà là chung cho  
   mỗi series trong nhóm ("thuộc tính nhóm series").  
   "Thuộc tính nhóm series" trong lớp ChartSeriesGroup là đọc/ghi.  
   Mỗi "thuộc tính nhóm series" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)