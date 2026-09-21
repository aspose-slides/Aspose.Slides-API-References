---
title: IStringChartValue class
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue lớp

Đại diện cho giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách:
            1) trong ô/ô của workbook liên quan đến biểu đồ;
            2) dưới dạng giá trị nguyên văn.

Kiểu IStringChartValue cung cấp các thành phần sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`as_literal_string`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/as_literal_string/) | Trả về hoặc đặt chuỗi nguyên văn nếu thuộc tính DataSourceType là DataSourceType.StringLiterals.<br/>            Đọc/ghi **str**. |
| [`as_cells`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/data/) |  |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`to_string(self)`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/to_string/#) | Trả về biểu diễn chuỗi. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Đặt giá trị từ ô được chỉ định. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/vi/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này sẽ trả về địa chỉ<br/>            của các ô trong workbook đại diện cho dữ liệu chuỗi. Nếu không, trả về<br/>            chuỗi rỗng. |

### Xem thêm
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)