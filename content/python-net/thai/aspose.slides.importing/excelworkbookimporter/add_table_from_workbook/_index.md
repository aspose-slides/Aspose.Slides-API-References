---
title: add_table_from_workbook method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
ดึงตารางจาก Excel workbook ที่ระบุและเพิ่มลงในตอนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

### คืนค่า

ตารางที่ถูกเพิ่มลงใน shape collection



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | shape collection ที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook) | ไฟล์ Excel workbook |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีตาราง |
| cell_range | **str** | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ มีค่าเป็น None หรือว่างเปล่า หรือเมื่อ worksheet หรือ cell range ที่ระบุไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อข้อมูลเข้าอยู่ในรูปแบบที่ไม่รองรับ |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
ดึงตารางจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตอนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

### คืนค่า

ตารางที่ถูกเพิ่มลงใน shape collection



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | shape collection ที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbook_path | **str** | พาธไปยังไฟล์ Excel workbook |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีตาราง |
| cell_range | **str** | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ มีค่าเป็น None หรือว่างเปล่า หรือเมื่อ worksheet หรือ cell range ที่ระบุไม่ถูกต้อง |
| **RuntimeError(Proxy error(IOException))** | เกิดเมื่อเกิดข้อผิดพลาด I/O ระหว่างการเข้าถึงไฟล์ workbook |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อข้อมูลเข้าอยู่ในรูปแบบที่ไม่รองรับ |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
ดึงตารางจากไฟล์ Excel workbook ที่ระบุและเพิ่มลงในตอนท้ายของ shape collection ที่กำหนดตามพิกัดที่ระบุ

### คืนค่า

ตารางที่ถูกเพิ่มลงใน shape collection



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | shape collection ที่ตารางจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับการวางตำแหน่งตาราง |
| y | **float** | พิกัด Y สำหรับการวางตำแหน่งตาราง |
| workbook_stream | **io.RawIOBase** | สตรีมที่บรรจุข้อมูล workbook |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีตาราง |
| cell_range | **str** | ช่วงเซลล์ที่กำหนดตาราง (เช่น "A1:D10") |

### ข้อยกเว้น

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ มีค่าเป็น None หรือว่างเปล่า หรือเมื่อ worksheet หรือ cell range ที่ระบุไม่ถูกต้อง |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดเมื่อข้อมูลเข้าอยู่ในรูปแบบที่ไม่รองรับ |



### ดูเพิ่มเติม
* คลาส [`ExcelWorkbookImporter`](/slides/python-net/th/aspose.slides.importing/excelworkbookimporter)
* คลาส [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* คลาส [`ITable`](/slides/python-net/th/aspose.slides/itable)
* โมดูล [`aspose.slides.importing`](/slides/python-net/th/aspose.slides.importing)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)