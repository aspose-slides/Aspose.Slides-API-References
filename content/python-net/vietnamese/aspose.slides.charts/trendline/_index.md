---
title: Trendline class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/trendline/
---
## Lớp Trendline

Lớp đại diện cho đường xu hướng của chuỗi biểu đồ

Kiểu Trendline cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`trendline_name`](/slides/python-net/vi/aspose.slides.charts/trendline/trendline_name/) | Lấy hoặc thiết lập tên của đường xu hướng.<br/>            Đọc/ghi **str**. |
| [`trendline_type`](/slides/python-net/vi/aspose.slides.charts/trendline/trendline_type/) | Lấy hoặc thiết lập loại đường xu hướng.<br/>            Đọc/ghi [`TrendlineType`](/slides/python-net/vi/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/vi/aspose.slides.charts/trendline/format/) | Đại diện cho định dạng của đường xu hướng.<br/>            Đọc/ghi [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/vi/aspose.slides.charts/trendline/backward/) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng kéo dài trước<br/>            dữ liệu của chuỗi đang được dự báo. Trên biểu đồ phân tán và không phân tán, giá trị phải là số không âm<br/>            bất kỳ.<br/>            Đọc/ghi **float**. |
| [`forward`](/slides/python-net/vi/aspose.slides.charts/trendline/forward/) | Xác định số danh mục (hoặc đơn vị trên biểu đồ phân tán) mà đường xu hướng kéo dài sau<br/>            dữ liệu của chuỗi đang được dự báo. Trên biểu đồ phân tán và không phân tán, giá trị phải là số không âm<br/>            bất kỳ.<br/>            Đọc/ghi **float**. |
| [`intercept`](/slides/python-net/vi/aspose.slides.charts/trendline/intercept/) | Xác định giá trị tại đó đường xu hướng sẽ cắt trục y. Thuộc tính này chỉ được hỗ trợ khi<br/>            loại đường xu hướng là exp, linear, hoặc poly.<br/>            Đọc/ghi **float**. |
| [`display_equation`](/slides/python-net/vi/aspose.slides.charts/trendline/display_equation/) | Xác định rằng phương trình của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với giá trị Rsquared).<br/>            Đọc/ghi **bool**. |
| [`order`](/slides/python-net/vi/aspose.slides.charts/trendline/order/) | Xác định bậc của đường xu hướng đa thức. Nó bị bỏ qua cho các loại đường xu hướng khác. Giá trị phải nằm giữa 2 và 6.<br/>            Đọc/ghi **int**. |
| [`period`](/slides/python-net/vi/aspose.slides.charts/trendline/period/) | Xác định chu kỳ của đường xu hướng cho đường xu hướng trung bình động. Nó bị bỏ qua cho các biến thể đường xu hướng khác.<br/>            Giá trị phải nằm giữa 2 và 255.<br/>            Đọc/ghi **int**. |
| [`display_r_squared_value`](/slides/python-net/vi/aspose.slides.charts/trendline/display_r_squared_value/) | Xác định rằng giá trị R-squared của đường xu hướng được hiển thị trên biểu đồ (trong cùng nhãn với phương trình).<br/>            Đọc/ghi **bool**. |
| [`related_legend_entry`](/slides/python-net/vi/aspose.slides.charts/trendline/related_legend_entry/) | Đại diện mục legend liên quan đến đường xu hướng này<br/>            Chỉ đọc [`ILegendEntryProperties`](/slides/python-net/vi/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/vi/aspose.slides.charts/trendline/text_frame_for_overriding/) | Có thể chứa văn bản định dạng phong phú. Nếu thuộc tính này không phải None thì giá trị văn bản định dạng này sẽ ghi đè văn bản tự động tạo của nhãn dữ liệu.<br/>            Văn bản tự động tạo của nhãn dữ liệu nghĩa là văn bản được quản lý bởi các thuộc tính ShowSeriesName,<br/>            ShowValue, ... và được định dạng bằng thuộc tính TextFormatManager.TextFormat.<br/>            Chỉ đọc [`ITextFrame`](/slides/python-net/vi/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/vi/aspose.slides.charts/trendline/text_format/) | Trả về định dạng văn bản.<br/>            Chỉ đọc [`IChartTextFormat`](/slides/python-net/vi/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/trendline/chart/) | Trả về biểu đồ cha.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/trendline/presentation/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/vi/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Khởi tạo TextFrameForOverriding với văn bản trong tham số "text".<br/>            Nếu TextFrameForOverriding đã được khởi tạo thì chỉ thay đổi văn bản của nó. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)