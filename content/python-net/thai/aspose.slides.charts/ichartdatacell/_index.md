---
title: IChartDataCell class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell คลาส

แทนเซลล์สำหรับข้อมูลแผนภูมิ

ประเภท IChartDataCell เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/row/) | ส่งคืนดัชนีของแถวในตารางงานที่เซลล์ตั้งอยู่.<br/>            อ่านอย่างเดียว **int**. |
| [`column`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/column/) | ส่งคืนดัชนีของคอลัมน์ในตารางงานที่เซลล์ตั้งอยู่.<br/>            อ่านอย่างเดียว **int**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/value/) | รับหรือกำหนดค่าของเซลล์.<br/>            อ่าน/เขียน **any**. |
| [`formula`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/formula/) | รับหรือกำหนดสูตรในรูปแบบ A1-style. |
| [`r1c1_formula`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/r1c1_formula/) | รับหรือกำหนดสูตรในรูปแบบ R1C1-style. |
| [`chart_data_worksheet`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | รับตารางงาน.<br/>            อ่านอย่างเดียว [`IChartDataWorksheet`](/slides/python-net/th/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/is_hidden/) | ระบุว่าเซลล์ถูกซ่อนหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`custom_number_format`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/custom_number_format/) | รับหรือกำหนดรูปแบบการแสดงผลที่กำหนดเองของตัวเลขและวันที่. <br/>            หากค่าเป็นค่าว่างจะใช้ค่า PresetNumberFormat.<br/>            อ่าน/เขียน **str**. |
| [`preset_number_format`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/preset_number_format/) | รับหรือกำหนดรูปแบบการแสดงผลที่มาพร้อมของตัวเลขและวันที่. Preset number must be in [0..22] or [37..49].<br/>            อ่าน/เขียน **int**. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/th/aspose.slides.charts/ichartdatacell/calculate/#bool) | หากเซลล์มีสูตร ค่า จะถูกอัปเดตตามสูตรนั้น. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)