---
title: ErrorBarsFormat class
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat lớp

Đại diện cho các thanh lỗi của chuỗi biểu đồ. Các giá trị tùy chỉnh của ErrorBars nằm trong IChartDataPointCollection (trong thuộc tính [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

Kiểu ErrorBarsFormat cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`type`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/type/) | Lấy hoặc đặt kiểu của các thanh lỗi. <br/>            Đọc/ghi [`ErrorBarType`](/slides/python-net/vi/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/value_type/) | Đại diện cho các cách có thể xác định chiều dài của các thanh lỗi. <br/>            Trong trường hợp kiểu giá trị tùy chỉnh để chỉ định giá trị, sử dụng thuộc tính [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/vi/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) của điểm dữ liệu cụ thể trong bộ sưu tập DataPoints của chuỗi.<br/>            Trong trường hợp kiểu giá trị Fixed, Percentage hoặc StandardDeviation, sử dụng thuộc tính Value để chỉ định giá trị.  <br/>            Đọc/ghi [`ErrorBarValueType`](/slides/python-net/vi/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/has_end_cap/) | Chỉ định rằng không vẽ đầu mũi trên các thanh lỗi.<br/>            Đọc/ghi **bool**. |
| [`value`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/value/) | Lấy hoặc đặt giá trị được sử dụng với các kiểu giá trị Fixed, Percentage và StandardDeviation để xác định chiều dài của các thanh lỗi. <br/>            Trong bất kỳ trường hợp nào khác sẽ trả về NaN.<br/>            Đọc/ghi **float**. |
| [`format`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/format/) | Đại diện cho định dạng của các thanh lỗi.<br/>            Đọc/ghi [`IFormat`](/slides/python-net/vi/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/chart/) | Trả về biểu đồ cha.<br/>            Chỉ đọc [`IChart`](/slides/python-net/vi/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/is_visible/) | Lấy hoặc đặt khả năng hiển thị của Error Bars.<br/>            Đọc/ghi **bool**. |
| [`slide`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/vi/aspose.slides.charts/errorbarsformat/presentation/) |  |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)