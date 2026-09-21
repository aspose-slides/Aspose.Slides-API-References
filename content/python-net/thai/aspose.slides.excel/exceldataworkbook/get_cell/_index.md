---
title: get_cell method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
ดึงเซลล์จาก worksheet ที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2").

### คืนค่า
เซลล์ที่ตำแหน่งที่ระบุ.

```python
def get_cell(self, worksheet_index, cell_name):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |

## get_cell(self, worksheet_name, cell_name) {#str-str}
ดึงเซลล์จาก worksheet ที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2").

### คืนค่า
เซลล์ที่ตำแหน่งที่ระบุ.

```python
def get_cell(self, worksheet_name, cell_name):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |

## get_cell(self, worksheet_index, row, column) {#int-int-int}
ดึงเซลล์จาก worksheet ที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์.

### คืนค่า
เซลล์ที่ตำแหน่งที่ระบุ.

```python
def get_cell(self, worksheet_index, row, column):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |

## get_cell(self, worksheet_name, row, column) {#str-int-int}
ดึงเซลล์จาก worksheet ที่ระบุโดยใช้ชื่อและพิกัดของเซลล์.

### คืนค่า
เซลล์ที่ตำแหน่งที่ระบุ.

```python
def get_cell(self, worksheet_name, row, column):
    ...
```

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |

### ดูเพิ่มเติม
* คลาส [`ExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook)
* คลาส [`IExcelDataCell`](/slides/python-net/th/aspose.slides.excel/iexceldatacell)
* โมดูล [`aspose.slides.excel`](/slides/python-net/th/aspose.slides.excel)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)