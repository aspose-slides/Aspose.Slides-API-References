---
title: IDataLabelFormat class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat lớp

Đại diện cho các tùy chọn định dạng cho DataLabel.

Kiểu IDataLabelFormat cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | Đọc/ghi **bool**. |
| [`number_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/number_format/) | Đại diện cho chuỗi định dạng của đối tượng DataLabels.<br/>            Đọc/ghi **str**. |
| [`format`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/format/) | Đại diện cho định dạng của nhãn dữ liệu.<br/>            Chỉ đọc [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/position/) | Đại diện cho vị trí của nhãn dữ liệu.<br/>            Đọc/ghi [`LegendDataLabelPosition`](/slides/python-net/vi/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_legend_key/) | Đại diện cho hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định. <br/>            True nếu khóa chú giải nhãn dữ liệu hiển thị.<br/>            Đọc/ghi **bool**. |
| [`show_value`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_value/) | Đại diện cho hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định. <br/>            True hiển thị giá trị phần trăm. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_category_name`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_category_name/) | Đại diện cho hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ được chỉ định.<br/>            True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_series_name`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_series_name/) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. <br/>            True để hiển thị tên chuỗi. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_percentage`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_percentage/) | Đại diện cho hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định. <br/>            True hiển thị giá trị phần trăm. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_bubble_size`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_bubble_size/) | Đại diện cho hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ được chỉ định. <br/>            True hiển thị giá trị kích thước bong bóng. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_leader_lines`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_leader_lines/) | Đại diện cho hành vi hiển thị các đường dẫn (leader lines) của nhãn dữ liệu trên biểu đồ được chỉ định. <br/>            True hiển thị các đường dẫn. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | Xác định liệu nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị như một data callout hay như một nhãn dữ liệu.<br/>            <br/>            Nếu phần tử cha của đối tượng DataLabelFormat này là một DataLabelCollection collection of data labels thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong DataLabelCollection collection.<br/>            Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout cho tất cả các nhãn dữ liệu trong DataLabelCollection collection<br/>            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" gây ra<br/>            all DataLabels[i].ShowLabelAsDataCallout is equal to val). |
| [`show_label_value_from_cell`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | Đại diện cho hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ được chỉ định. <br/>            True hiển thị giá trị ô. False để ẩn.<br/>            Đọc/ghi **bool**. |
| [`separator`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/separator/) | Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ.<br/>            Đọc/ghi **str**. |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/idatalabelformat/presentation/) |  |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)