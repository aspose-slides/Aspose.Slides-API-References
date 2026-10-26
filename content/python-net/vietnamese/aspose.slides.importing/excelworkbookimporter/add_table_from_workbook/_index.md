---
title: add_table_from_workbook method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Lấy một bảng từ workbook Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình dạng.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập hình dạng mà bảng sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị bảng. |
| y | **float** | Tọa độ Y để định vị bảng. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook) | Workbook Excel. |
| worksheet_name | **str** | Tên của worksheet chứa bảng. |
| cell_range | **str** | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số nào bắt buộc nào là None hoặc rỗng, hoặc khi worksheet hoặc phạm vi ô được chỉ định không hợp lệ. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Lấy một bảng từ tệp workbook Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình dạng.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập hình dạng mà bảng sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị bảng. |
| y | **float** | Tọa độ Y để định vị bảng. |
| workbook_path | **str** | Đường dẫn tới tệp workbook Excel. |
| worksheet_name | **str** | Tên của worksheet chứa bảng. |
| cell_range | **str** | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số nào bắt buộc nào là None hoặc rỗng, hoặc khi worksheet hoặc phạm vi ô được chỉ định không hợp lệ. |
| **RuntimeError(Proxy error(IOException))** | Bị ném khi xảy ra lỗi I/O trong khi truy cập tệp workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Lấy một bảng từ tệp workbook Excel được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng đã cho tại các tọa độ được chỉ định.

### Giá trị trả về

Bảng đã được thêm vào bộ sưu tập hình dạng.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập hình dạng mà bảng sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị bảng. |
| y | **float** | Tọa độ Y để định vị bảng. |
| workbook_stream | **io.RawIOBase** | Luồng chứa dữ liệu workbook. |
| worksheet_name | **str** | Tên của worksheet chứa bảng. |
| cell_range | **str** | Phạm vi ô xác định bảng (ví dụ, "A1:D10"). |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số nào bắt buộc nào là None hoặc rỗng, hoặc khi worksheet hoặc phạm vi ô được chỉ định không hợp lệ. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi dữ liệu đầu vào ở định dạng không được hỗ trợ. |



### Xem thêm
* lớp [`ExcelWorkbookImporter`](/slides/python-net/vi/aspose.slides.importing/excelworkbookimporter)
* lớp [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* lớp [`ITable`](/slides/python-net/vi/aspose.slides/itable)
* mô-đun [`aspose.slides.importing`](/slides/python-net/vi/aspose.slides.importing)
* thư viện [`Aspose.Slides`](/slides/python-net)