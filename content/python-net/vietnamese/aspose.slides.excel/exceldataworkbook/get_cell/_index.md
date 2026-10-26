---
title: get_cell method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
Lấy một ô từ bảng tính được chỉ định bằng chỉ số và tên ô theo kiểu Excel (ví dụ, "B2").

### Trả về

Ô tại vị trí được chỉ định.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_index | **int** | Chỉ số bảng tính, bắt đầu từ 0. |
| cell_name | **str** | Tham chiếu ô theo kiểu Excel (ví dụ, "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Lấy một ô từ bảng tính được chỉ định bằng tên ô theo kiểu Excel (ví dụ, "B2").

### Trả về

Ô tại vị trí được chỉ định.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_name | **str** | Tên của bảng tính. |
| cell_name | **str** | Tham chiếu ô theo kiểu Excel (ví dụ, "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
Lấy một ô từ bảng tính được chỉ định bằng chỉ số và tọa độ ô.

### Trả về

Ô tại vị trí được chỉ định.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_index | **int** | Chỉ số bảng tính, bắt đầu từ 0. |
| row | **int** | Chỉ số hàng của ô, bắt đầu từ 0. |
| column | **int** | Chỉ số cột của ô, bắt đầu từ 0. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
Lấy một ô từ bảng tính được chỉ định bằng tên và tọa độ ô.

### Trả về

Ô tại vị trí được chỉ định.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| worksheet_name | **str** | Tên của bảng tính. |
| row | **int** | Chỉ số hàng của ô, bắt đầu từ 0. |
| column | **int** | Chỉ số cột của ô, bắt đầu từ 0. |



### Xem thêm
* lớp [`ExcelDataWorkbook`](/slides/python-net/vi/aspose.slides.excel/exceldataworkbook)
* lớp [`IExcelDataCell`](/slides/python-net/vi/aspose.slides.excel/iexceldatacell)
* mô-đun [`aspose.slides.excel`](/slides/python-net/vi/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)