---
title: get_cell method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2")。

### ผลลัพธ์

เซลล์ที่ตำแหน่งที่ระบุ



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_index | **int** | ดัชนีเริ่มจากศูนย์ของเวิร์กชีต |
| cell_name | **str** | การอ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |


## get_cell(self, worksheet_name, cell_name) {#str-str}
ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2")。

### ผลลัพธ์

เซลล์ที่ตำแหน่งที่ระบุ



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_name | **str** | ชื่อของเวิร์กชีต |
| cell_name | **str** | การอ้างอิงเซลล์แบบ Excel (เช่น "A1", "C5") |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์。

### ผลลัพธ์

เซลล์ที่ตำแหน่งที่ระบุ



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_index | **int** | ดัชนีเริ่มจากศูนย์ของเวิร์กชีต |
| row | **int** | ดัชนีแถวเริ่มจากศูนย์ของเซลล์ |
| column | **int** | ดัชนีคอลัมน์เริ่มจากศูนย์ของเซลล์ |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์。

### ผลลัพธ์

เซลล์ที่ตำแหน่งที่ระบุ



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_name | **str** | ชื่อของเวิร์กชีต |
| row | **int** | ดัชนีแถวเริ่มจากศูนย์ของเซลล์ |
| column | **int** | ดัชนีคอลัมน์เริ่มจากศูนย์ของเซลล์ |



### ดูเพิ่มเติม
* class [`IExcelDataCell`](/slides/python-net/th/aspose.slides.excel/iexceldatacell)
* class [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook)
* module [`aspose.slides.excel`](/slides/python-net/th/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)