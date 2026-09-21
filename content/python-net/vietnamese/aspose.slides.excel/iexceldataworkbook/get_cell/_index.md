---
title: get_cell method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Trích xuất một ô từ bảng tính được chỉ định bằng chỉ mục và tên ô theo kiểu Excel (ví dụ: "B2").

### Giá trị trả về

Ô ở vị trí đã chỉ định.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_index | **int** | Chỉ mục bắt đầu từ 0 của bảng tính. |
| cell_name | **str** | Tham chiếu ô theo kiểu Excel (ví dụ: "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Trích xuất một ô từ bảng tính được chỉ định bằng tên bảng tính và tên ô theo kiểu Excel (ví dụ: "B2").

### Giá trị trả về

Ô ở vị trí đã chỉ định.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_name | **str** | Tên của bảng tính. |
| cell_name | **str** | Tham chiếu ô theo kiểu Excel (ví dụ: "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Trích xuất một ô từ bảng tính được chỉ định bằng chỉ mục và tọa độ ô.

### Giá trị trả về

Ô ở vị trí đã chỉ định.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_index | **int** | Chỉ mục bắt đầu từ 0 của bảng tính. |
| row | **int** | Chỉ mục hàng bắt đầu từ 0 của ô. |
| column | **int** | Chỉ mục cột bắt đầu từ 0 của ô. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Trích xuất một ô từ bảng tính được chỉ định bằng tên và tọa độ ô.

### Giá trị trả về

Ô ở vị trí đã chỉ định.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_name | **str** | Tên của bảng tính. |
| row | **int** | Chỉ mục hàng bắt đầu từ 0 của ô. |
| column | **int** | Chỉ mục cột bắt đầu từ 0 của ô. |



### Xem thêm
* lớp [`IExcelDataCell`](/slides/python-net/vi/aspose.slides.excel/iexceldatacell)
* lớp [`IExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/iexceldataworkbook)
* module [`aspose.slides.excel`](/slides/python-net/vi/aspose.slides.excel)
* thư viện [`Aspose.Slides`](/slides/python-net)