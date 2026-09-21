---
title: add_chart_from_workbook method
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
ดึงแผนภูมิจาก Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดที่ตำแหน่งพิกัดที่ระบุ

### ผลลัพธ์

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | คอลเลกชันของ shape ที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับวางแผนภูมิ |
| y | **float** | พิกัด Y สำหรับวางแผนภูมิ |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook) | workbook ของ Excel |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีแผนภูมิอยู่ |
| chart_index | **int** | ดัชนีที่เริ่มจากศูนย์ของรูปแผนภูมิที่ต้องแทรก. <br/><br/>            This index can be obtained using the **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** method. |
| embed_all_workbook | **bool** | หาก `true` workbook ทั้งหมดจะถูกฝังในแผนภูมิ; <br/><br/>            หาก `false` จะฝังเฉพาะข้อมูลของแผนภูมิเท่านั้น. |

### ข้อยกเว้น

| Exception | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น None, ว่างเปล่า, หรือหากไม่พบแผนภูมิใน workbook. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
ดึงแผนภูมิจาก Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดที่ตำแหน่งพิกัดที่ระบุ

### ผลลัพธ์

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | คอลเลกชันของ shape ที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับวางแผนภูมิ |
| y | **float** | พิกัด Y สำหรับวางแผนภูมิ |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook) | workbook ของ Excel |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีแผนภูมิอยู่ |
| chart_name | **str** | ชื่อของแผนภูมิที่จะเพิ่ม |
| embed_all_workbook | **bool** | หาก `true` workbook ทั้งหมดจะถูกฝังในแผนภูมิ; <br/><br/>            หาก `false` จะฝังเฉพาะข้อมูลของแผนภูมิเท่านั้น. |

### ข้อยกเว้น

| Exception | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น None, ว่างเปล่า, หรือหากไม่พบแผนภูมิใน workbook. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
ดึงแผนภูมิจาก Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดที่ตำแหน่งพิกัดที่ระบุ

### ผลลัพธ์

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | คอลเลกชันของ shape ที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับวางแผนภูมิ |
| y | **float** | พิกัด Y สำหรับวางแผนภูมิ |
| workbook_stream | **io.RawIOBase** | สตรีมที่มีข้อมูลของ workbook |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีแผนภูมิอยู่ |
| chart_name | **str** | ชื่อของแผนภูมิที่จะเพิ่ม |
| embed_all_workbook | **bool** | หาก `true` workbook ทั้งหมดจะถูกฝังในแผนภูมิ; <br/><br/>            หาก `false` จะฝังเฉพาะข้อมูลของแผนภูมิเท่านั้น. |

### ข้อยกเว้น

| Exception | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น None, ว่างเปล่า, หรือหากไม่พบแผนภูมิใน workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดข้อผิดพลาดเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
ดึงแผนภูมิจาก Excel workbook ที่ระบุและเพิ่มลงในส่วนท้ายของ shape collection ที่กำหนดที่ตำแหน่งพิกัดที่ระบุ

### ผลลัพธ์

แผนภูมิที่ถูกเพิ่มเข้าไปใน shape collection



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| พารามิเตอร์ | ประเภท | รายละเอียด |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection) | คอลเลกชันของ shape ที่แผนภูมิจะถูกเพิ่มเข้าไป |
| x | **float** | พิกัด X สำหรับวางแผนภูมิ |
| y | **float** | พิกัด Y สำหรับวางแผนภูมิ |
| workbook_path | **str** | เส้นทางไฟล์ไปยัง workbook ที่มีแผนภูมิ |
| worksheet_name | **str** | ชื่อของ worksheet ที่มีแผนภูมิอยู่ |
| chart_name | **str** | ชื่อของแผนภูมิที่จะเพิ่ม |
| embed_workbook | **bool** | หาก `true` workbook จะถูกฝังในแผนภูมิ; <br/><br/>            หาก `false` แผนภูมิจะเชื่อมโยงไปยัง workbook ภายนอก. |

### ข้อยกเว้น

| Exception | รายละเอียด |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | เกิดข้อผิดพลาดเมื่อพารามิเตอร์ที่จำเป็นใด ๆ เป็น None, ว่างเปล่า, หรือหากไม่พบแผนภูมิใน workbook. |
| **RuntimeError(Proxy error(IOException))** | เกิดข้อผิดพลาด I/O ขณะเข้าถึงไฟล์. |
| **RuntimeError(Proxy error(InvalidOperationException))** | เกิดข้อผิดพลาดเมื่อข้อมูลอินพุตอยู่ในรูปแบบที่ไม่รองรับ. |



### ดูเพิ่มเติม
* คลาส [`ExcelWorkbookImporter`](/slides/python-net/th/aspose.slides.importing/excelworkbookimporter)
* คลาส [`IExcelDataWorkbook`](/slides/python-net/th/aspose.slides.excel/iexceldataworkbook)
* คลาส [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection)
* โมดูล [`aspose.slides.importing`](/slides/python-net/th/aspose.slides.importing)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)