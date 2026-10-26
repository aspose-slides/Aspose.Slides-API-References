---
title: ExcelDataWorkbook class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook lớp

Biểu diễn một workbook cung cấp quyền truy cập vào dữ liệu Excel cho việc sử dụng chung.

Kiểu ExcelDataWorkbook cung cấp các thành viên sau:

## Constructors

| Phương thức khởi tạo | Mô tả |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/__init__/#str) | Khởi tạo một thể hiện mới bằng cách sử dụng đường dẫn tệp được chỉ định. |
| [`__init__(self, stream)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Khởi tạo một thể hiện mới của lớp bằng cách sử dụng luồng đã cung cấp. |

## Methods

| Phương thức | Mô tả |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Lấy một ô từ worksheet được chỉ định bằng cách sử dụng chỉ mục và tọa độ ô. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Lấy một ô từ worksheet được chỉ định bằng cách sử dụng tên và tọa độ ô. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Lấy một ô từ worksheet được chỉ định bằng cách sử dụng chỉ mục và tên ô theo kiểu Excel (ví dụ: "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Lấy một ô từ worksheet được chỉ định bằng tên ô theo kiểu Excel (ví dụ: "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Lấy một tập hợp các ô từ workbook khớp với công thức được chỉ định. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Lấy một từ điển chứa các chỉ mục và tên của tất cả biểu đồ trong worksheet được chỉ định của một workbook Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Lấy tên của tất cả worksheet chứa trong workbook Excel. |

### Xem thêm
* module [`aspose.slides.excel`](/slides/python-net/vi/aspose.slides.excel)
* thư viện [`Aspose.Slides`](/slides/python-net)