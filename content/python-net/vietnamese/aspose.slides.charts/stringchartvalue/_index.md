---
title: StringChartValue class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/stringchartvalue/
---
## Lớp StringChartValue

Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách:
            1) trong ô/ô của bảng tính liên quan đến biểu đồ;
            2) dưới dạng giá trị nguyên mẫu.

**Kế thừa:**[`StringChartValue`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/vi/aspose.slides.charts/basechartvalue)

Kiểu StringChartValue khai báo các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`data_source_type`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/data_source_type/) | Chỉ định liệu thuộc tính AsCell, AsCells, AsLiteralString hoặc AsLiteralDouble <br/>            có thực trong các lớp con hay không. Nói cách khác, nó chỉ định kiểu <br/>            của giá trị thuộc tính Data.<br/>            Đọc/ghi [`DataSourceType`](/slides/python-net/vi/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/data/) | Trả về hoặc đặt đối tượng Data.<br/>            Đọc/ghi **any**. |
| [`as_cells`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/as_cells/) | Không cho phép gán giá trị null.<br/>            Giá trị trả về luôn không phải None.<br/>            Đọc/ghi [`IChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/as_literal_string/) | Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên mẫu.<br/>            Đọc/ghi **str**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Đặt giá trị từ ô đã chỉ định. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Nếu thuộc tính DataSourceType có giá trị DataSourceType.Worksheet thì phương thức này trả về địa chỉ<br/>            của các ô trong bảng tính đại diện cho dữ liệu chuỗi. Ngược lại trả về<br/>            chuỗi rỗng. |

### Xem thêm
* lớp [`BaseChartValue`](/slides/python-net/vi/aspose.slides.charts/basechartvalue)
* lớp [`StringChartValue`](/slides/python-net/vi/aspose.slides.charts/stringchartvalue)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)