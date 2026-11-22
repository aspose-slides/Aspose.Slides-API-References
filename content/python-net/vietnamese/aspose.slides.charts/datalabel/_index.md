---
title: DataLabel class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/datalabel/
---
## DataLabel lớp

Biểu diễn các nhãn chuỗi.

Kiểu DataLabel cung cấp các thành viên sau:

## Hàm khởi tạo

| Constructor | Mô tả |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/vi/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Tạo một thể hiện mới của lớp DataLabel. |

## Thuộc tính

| Property | Mô tả |
| :- | :- |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/datalabel/chart/) | Trả về biểu đồ cha.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/datalabel/is_visible/) | False có nghĩa là nhãn dữ liệu không hiển thị (và do đó tất cả các cờ Show*-flags (ShowValue, ...) đều là false).<br/>            Chỉ đọc **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/vi/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Có thể chứa văn bản được định dạng phong phú. Nếu thuộc tính này không phải None thì giá trị văn bản định dạng này sẽ ghi đè văn bản tự động tạo của nhãn dữ liệu.<br/>            Văn bản tự động tạo của nhãn dữ liệu là văn bản được quản lý bởi các thuộc tính ShowSeriesName, <br/>            ShowValue, ... và được định dạng bằng thuộc tính TextFormatManager.TextFormat.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/datalabel/text_format/) | Trả về định dạng văn bản.<br/>            Chỉ đọc [`IChartTextFormat`](/slides/python-net/vi/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/vi/aspose.slides.charts/datalabel/x/) | Trả về hoặc đặt tọa độ x của tiêu đề dưới dạng tỷ lệ phần trăm của chiều rộng biểu đồ.<br/>            Đọc/ghi **float**. |
| [`y`](/slides/python-net/vi/aspose.slides.charts/datalabel/y/) | Trả về hoặc đặt tọa độ y của tiêu đề dưới dạng tỷ lệ phần trăm của chiều cao biểu đồ.<br/>            Đọc/ghi **float**. |
| [`width`](/slides/python-net/vi/aspose.slides.charts/datalabel/width/) | Trả về hoặc đặt chiều rộng của tiêu đề dưới dạng tỷ lệ phần trăm của chiều rộng biểu đồ.<br/>            Đọc/ghi **float**. |
| [`height`](/slides/python-net/vi/aspose.slides.charts/datalabel/height/) | Trả về hoặc đặt chiều cao của tiêu đề dưới dạng tỷ lệ phần trăm của chiều cao biểu đồ.<br/>            Đọc/ghi **float**. |
| [`right`](/slides/python-net/vi/aspose.slides.charts/datalabel/right/) | Phải.<br/>            Chỉ đọc **float**. |
| [`bottom`](/slides/python-net/vi/aspose.slides.charts/datalabel/bottom/) | Dưới.<br/>            Chỉ đọc **float**. |
| [`data_label_format`](/slides/python-net/vi/aspose.slides.charts/datalabel/data_label_format/) | Trả về định dạng nhãn dữ liệu.<br/>            Chỉ đọc [`IDataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/vi/aspose.slides.charts/datalabel/value_from_cell/) | Lấy hoặc đặt ô dữ liệu workbook. Được áp dụng khi thuộc tính IDataLabelFormat.ShowLabelValueFromCell bằng true. |
| [`label_shape_type`](/slides/python-net/vi/aspose.slides.charts/datalabel/label_shape_type/) | Lấy hoặc đặt kiểu hình dạng của nhãn dữ liệu.<br/>             Trả về [`ShapeType.NOT_DEFINED`](/slides/python-net/vi/aspose.slides/shapetype/NOT_DEFINED) nếu không có hình dạng nào được định nghĩa. |
| [`actual_x`](/slides/python-net/vi/aspose.slides.charts/datalabel/actual_x/) | Xác định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ.<br/>            Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_y`](/slides/python-net/vi/aspose.slides.charts/datalabel/actual_y/) | Xác định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ.<br/>            Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_width`](/slides/python-net/vi/aspose.slides.charts/datalabel/actual_width/) | Xác định chiều rộng thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`actual_height`](/slides/python-net/vi/aspose.slides.charts/datalabel/actual_height/) | Xác định chiều cao thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.<br/>            Đọc **float**. |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/datalabel/presentation/) |  |

## Phương thức

| Method | Mô tả |
| :- | :- |
| [`hide(self)`](/slides/python-net/vi/aspose.slides.charts/datalabel/hide/#) | Ẩn nhãn dữ liệu bằng cách đặt tất cả các cờ Show*-flags (ShowValue, ...) về trạng thái false.<br/>            IsVisible sẽ thành false sau thao tác này. |
| [`get_actual_label_text(self)`](/slides/python-net/vi/aspose.slides.charts/datalabel/get_actual_label_text/#) | Trả về văn bản nhãn thực tế dựa trên cài đặt DataLabelFormat hoặc giá trị TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/vi/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Khởi tạo TextFrameForOverriding với văn bản trong tham số "text".<br/>            Nếu TextFrameForOverriding đã được khởi tạo, thì chỉ đơn giản thay đổi văn bản của nó. |


### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)