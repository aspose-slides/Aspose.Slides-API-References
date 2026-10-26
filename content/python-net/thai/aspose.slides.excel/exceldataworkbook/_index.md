---
title: ExcelDataWorkbook class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook คลาส

แสดงถึงเวิร์กบุ๊กที่ให้การเข้าถึงข้อมูล Excel สำหรับการใช้งานทั่วไป.

ประเภท ExcelDataWorkbook เปิดเผยสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | คำอธิบาย |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/__init__/#str) | สร้างอินสแตนซ์ใหม่โดยใช้เส้นทางไฟล์ที่ระบุ. |
| [`__init__(self, stream)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | สร้างอินสแตนซ์ใหม่ของคลาสโดยใช้สตรีมที่ให้มา. |

## เมธอด

| Method | คำอธิบาย |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและพิกัดของเซลล์. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อและพิกัดของเซลล์. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ดัชนีและชื่อเซลล์แบบ Excel (เช่น "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | ดึงเซลล์จากเวิร์กชีตที่ระบุโดยใช้ชื่อเซลล์แบบ Excel (เช่น "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | ดึงคอลเลกชันของเซลล์จากเวิร์กบุ๊กที่ตรงกับสูตรที่ระบุ. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | ดึงพจนานุกรมที่มีดัชนีและชื่อของแผนภูมิทั้งหมดในเวิร์กชีตที่ระบุของเวิร์กบุ๊ก Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/th/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | ดึงชื่อของเวิร์กชีตทั้งหมดที่อยู่ในเวิร์กบุ๊ก Excel. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.excel`](/slides/python-net/th/aspose.slides.excel)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)