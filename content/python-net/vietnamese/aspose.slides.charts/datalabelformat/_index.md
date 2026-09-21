---
title: DataLabelFormat class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat lớp

Biểu diễn các tùy chọn định dạng cho DataLabel.

**Kế thừa:**[`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)

Kiểu DataLabelFormat cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | Đọc/ghi **bool**. |
| [`number_format`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/number_format/) | Biểu diễn chuỗi định dạng cho đối tượng DataLabels.<br/>            Đọc/ghi **str**. |
| [`format`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/format/) | Biểu diễn định dạng của nhãn dữ liệu.<br/>            Chỉ đọc [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/position/) | Biểu diễn vị trí của nhãn dữ liệu.<br/>            Đọc/ghi [`LegendDataLabelPosition`](/slides/python-net/vi/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_legend_key/) | Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định.<br/>            True nếu khóa chú giải nhãn dữ liệu hiển thị.<br/>            Đọc/ghi **bool**. |
| [`show_value`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_value/) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị giá trị phần trăm. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_category_name`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_category_name/) | Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị tên danh mục. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_series_name`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_series_name/) | Trả về hoặc đặt Boolean để chỉ định hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ.<br/>            True hiển thị tên chuỗi. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_percentage`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_percentage/) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị giá trị phần trăm. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_bubble_size`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_bubble_size/) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị giá trị kích thước bong bóng. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_leader_lines`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_leader_lines/) | Biểu diễn hành vi hiển thị đường dẫn của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị đường dẫn. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True hiển thị giá trị ô. False ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | Xác định liệu nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị dưới dạng chú thích dữ liệu hay là nhãn dữ liệu.<br/>            <br/>            Nếu cha của đối tượng DataLabelFormat này là một collection DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong collection DataLabelCollection.<br/>            Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout cho tất cả các nhãn dữ liệu trong collection DataLabelCollection<br/>            (ví dụ: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" gây ra<br/>            tất cả DataLabels[i].ShowLabelAsDataCallout bằng val). |
| [`separator`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/separator/) | Đặt hoặc trả về Variant biểu diễn dấu phân cách được sử dụng cho các nhãn dữ liệu trên biểu đồ.<br/>            Đọc/ghi **str**. |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/text_format/) | Trả về định dạng văn bản của biểu đồ.<br/>            Chỉ đọc [`IChartTextFormat`](/slides/python-net/vi/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/chart/) | Trả về biểu đồ.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/datalabelformat/presentation/) |  |

### Xem Thêm
* lớp [`DataLabelFormat`](/slides/python-net/vi/aspose.slides.charts/datalabelformat)
* lớp [`PVIObject`](/slides/python-net/vi/aspose.slides/pviobject)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)