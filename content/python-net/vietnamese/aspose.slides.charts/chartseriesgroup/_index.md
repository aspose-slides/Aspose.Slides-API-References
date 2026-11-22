---
title: ChartSeriesGroup class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup lớp

Biểu diễn nhóm các chuỗi.

Kiểu ChartSeriesGroup hiển thị các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/type/) | Trả về kiểu của nhóm chuỗi này.<br/>            Chỉ đọc [`CombinableSeriesTypesGroup`](/slides/python-net/vi/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Cho biết nếu các chuỗi của nhóm này được vẽ trên trục phụ.<br/>            Chỉ đọc **bool**. |
| [`series`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/series/) | Trả về một tập hợp các chuỗi.<br/>            Chỉ đọc [`IChartSeriesReadonlyCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu.<br/>            Chỉ đọc [`IUpDownBarsManager`](/slides/python-net/vi/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/gap_width/) | Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột.<br/>            Giá trị phải nằm trong khoảng từ 0 đến 500.<br/>            Đọc/ghi **int**. |
| [`gap_depth`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/gap_depth/) | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của marker.<br/>            Giá trị phải nằm trong khoảng từ 0 đến 500.<br/>            Đọc/ghi **int**. |
| [`first_slice_angle`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Lấy hoặc đặt góc của mảnh bánh hoặc vòng donut đầu tiên, <br/>            tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ).<br/>            Đọc/ghi **int**. |
| [`doughnut_hole_size`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 0 đến 90 phần trăm <br/>            của kích thước vùng vẽ).<br/>            Đọc/ghi **int**. |
| [`overlap`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/overlap/) | Xác định mức độ các thanh và cột sẽ chồng lên nhau trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%).<br/>             - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời).<br/>             - 0%: Các thanh được đặt cạnh nhau mà không có chồng lấn hoặc khoảng cách.<br/>             - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau).<br/>             Thuộc tính này là Đọc/ghi **int**. |
| [`second_pie_size`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc biểu đồ thanh-con-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200 phần trăm).<br/>            Đọc/ghi **int**. |
| [`bubble_size_representation`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng.<br/>            Đọc/ghi [`BubbleSizeRepresentationType`](/slides/python-net/vi/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Xác định một giá trị sẽ được dùng để quyết định dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. <br/>            Được sử dụng cùng với thuộc tính PieSplitBy.<br/>            Đọc/ghi **float**. |
| [`pie_split_by`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Xác định cách quyết định dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh.<br/>            Đọc/ghi [`PieSplitType`](/slides/python-net/vi/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Xác định rằng mỗi marker dữ liệu trong chuỗi có màu khác nhau.<br/>            Đọc/ghi **bool**. |
| [`has_series_lines`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Đúng nếu biểu đồ có đường chuỗi. Áp dụng cho biểu đồ cột xếp chồng và OfPie.<br/>            Đọc/ghi **bool**. |
| [`hi_low_lines_format`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Xác định định dạng HiLowLines. <br/>            HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 phần trăm kích thước mặc định).<br/>            Đọc/ghi **int**. |
| [`pie_split_custom_points`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Thông tin chia tách tùy chỉnh cho biểu đồ bánh-con-bánh hoặc thanh-con-bánh có chia tách tùy chỉnh.<br/>            Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc <br/>            thanh-con-bánh.<br/>            Chỉ đọc [`PieSplitCustomPointCollection`](/slides/python-net/vi/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/chart/) | Trả về biểu đồ cha.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Lấy phần tử tại chỉ mục đã chỉ định.

## Trình chỉ mục

| Tên | Mô tả |
| :- | :- |
| [`[index]`](/slides/python-net/vi/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Ghi chú

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup.
            2) Nhóm các chuỗi chứa một số thuộc tính chuỗi chung cho 
            mỗi chuỗi trong nhóm ("series group properties").
            "Series group properties" trong lớp ChartSeriesGroup là Đọc/ghi.
            Mỗi "series group properties" có thể có một chiếu chỉ đọc trong lớp ChartSeries.

### Xem thêm
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)