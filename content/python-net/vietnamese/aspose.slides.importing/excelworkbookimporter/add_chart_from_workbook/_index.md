---
title: add_chart_from_workbook method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Truy xuất một biểu đồ từ workbook Excel đã chỉ định và thêm nó vào cuối bộ sưu tập shape đã cho tại các tọa độ đã chỉ định.

### Trả về

Biểu đồ đã được thêm vào bộ sưu tập shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập shape mà biểu đồ sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị biểu đồ. |
| y | **float** | Tọa độ Y để định vị biểu đồ. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook) | Workbook Excel. |
| worksheet_name | **str** | Tên của worksheet chứa biểu đồ. |
| chart_index | **int** | Chỉ mục không dựa trên zero của shape biểu đồ cần chèn. <br/><br/>            Chỉ mục này có thể lấy bằng phương thức **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Nếu `true`, toàn bộ workbook sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số bắt buộc nào là None, rỗng, hoặc khi không tìm thấy biểu đồ trong workbook. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Truy xuất một biểu đồ từ workbook Excel đã chỉ định và thêm nó vào cuối bộ sưu tập shape đã cho tại các tọa độ đã chỉ định.

### Trả về

Biểu đồ đã được thêm vào bộ sưu tập shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập shape mà biểu đồ sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị biểu đồ. |
| y | **float** | Tọa độ Y để định vị biểu đồ. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook) | Workbook Excel. |
| worksheet_name | **str** | Tên của worksheet chứa biểu đồ. |
| chart_name | **str** | Tên của biểu đồ sẽ được thêm. |
| embed_all_workbook | **bool** | Nếu `true`, toàn bộ workbook sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số bắt buộc nào là None, rỗng, hoặc khi không tìm thấy biểu đồ trong workbook. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Truy xuất một biểu đồ từ workbook Excel đã chỉ định và thêm nó vào cuối bộ sưu tập shape đã cho tại các tọa độ đã chỉ định.

### Trả về

Biểu đồ đã được thêm vào bộ sưu tập shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập shape mà biểu đồ sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị biểu đồ. |
| y | **float** | Tọa độ Y để định vị biểu đồ. |
| workbook_stream | **io.RawIOBase** | Luồng chứa dữ liệu workbook. |
| worksheet_name | **str** | Tên của worksheet chứa biểu đồ. |
| chart_name | **str** | Tên của biểu đồ sẽ được thêm. |
| embed_all_workbook | **bool** | Nếu `true`, toàn bộ workbook sẽ được nhúng vào biểu đồ; nếu `false`, chỉ dữ liệu biểu đồ sẽ được nhúng. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số bắt buộc nào là None, rỗng, hoặc khi không tìm thấy biểu đồ trong workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi dữ liệu đầu vào có định dạng không được hỗ trợ. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Truy xuất một biểu đồ từ workbook Excel đã chỉ định và thêm nó vào cuối bộ sưu tập shape đã cho tại các tọa độ đã chỉ định.

### Trả về

Biểu đồ đã được thêm vào bộ sưu tập shape.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection) | Bộ sưu tập shape mà biểu đồ sẽ được thêm vào. |
| x | **float** | Tọa độ X để định vị biểu đồ. |
| y | **float** | Tọa độ Y để định vị biểu đồ. |
| workbook_path | **str** | Đường dẫn tệp tới workbook chứa biểu đồ. |
| worksheet_name | **str** | Tên của worksheet chứa biểu đồ. |
| chart_name | **str** | Tên của biểu đồ sẽ được thêm. |
| embed_workbook | **bool** | Nếu `true`, workbook sẽ được nhúng vào biểu đồ; nếu `false`, biểu đồ sẽ liên kết tới workbook bên ngoài. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném khi bất kỳ tham số bắt buộc nào là None, rỗng, hoặc khi không tìm thấy biểu đồ trong workbook. |
| **RuntimeError(Proxy error(IOException))** | Bị ném khi xảy ra lỗi I/O trong quá trình truy cập tệp. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi dữ liệu đầu vào có định dạng không được hỗ trợ. |



### Xem thêm
* lớp [`ExcelWorkbookImporter`](/slides/python-net/vi/aspose.slides.importing/excelworkbookimporter)
* lớp [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* mô-đun [`aspose.slides.importing`](/slides/python-net/vi/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)