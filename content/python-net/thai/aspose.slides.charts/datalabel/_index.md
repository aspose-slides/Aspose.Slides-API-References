---
title: DataLabel class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/datalabel/
---
## คลาส DataLabel

เป็นตัวแทนของป้ายกำกับของชุดข้อมูล

ประเภท DataLabel เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| Constructor | Description |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/th/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | สร้างอินสแตนซ์ใหม่ของคลาส DataLabel. |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/th/aspose.slides.charts/datalabel/chart/) | ส่งคืนแผนภูมิต้นแบบ.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/datalabel/is_visible/) | ค่า False หมายความว่าป้ายข้อมูลไม่ปรากฏ (และจึงทุกแฟล็ก Show*-flags (ShowValue, ...) จะเป็น false).<br/>            อ่านอย่างเดียว **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/th/aspose.slides.charts/datalabel/text_frame_for_overriding/) | สามารถมีข้อความที่มีรูปแบบหลายรูปแบบได้ หากคุณสมบัตินี้ไม่เป็น None แล้วค่าข้อความที่จัดรูปแบบนี้จะละเว้นข้อความที่สร้างอัตโนมัติของป้ายข้อมูล.<br/>            ข้อความที่สร้างอัตโนมัติของป้ายข้อมูลหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, <br/>            ShowValue, ... และถูกจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/datalabel/text_format/) | ส่งคืนรูปแบบข้อความ.<br/>            อ่านอย่างเดียว [`IChartTextFormat`](/slides/python-net/th/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/th/aspose.slides.charts/datalabel/x/) | ส่งคืนหรือกำหนดพิกัด x ของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides.charts/datalabel/y/) | ส่งคืนหรือกำหนดพิกัด y ของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides.charts/datalabel/width/) | ส่งคืนหรือกำหนดความกว้างของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides.charts/datalabel/height/) | ส่งคืนหรือกำหนดความสูงของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ.<br/>            อ่าน/เขียน **float**. |
| [`right`](/slides/python-net/th/aspose.slides.charts/datalabel/right/) | ด้านขวา.<br/>            อ่านอย่างเดียว **float**. |
| [`bottom`](/slides/python-net/th/aspose.slides.charts/datalabel/bottom/) | ด้านล่าง.<br/>            อ่านอย่างเดียว **float**. |
| [`data_label_format`](/slides/python-net/th/aspose.slides.charts/datalabel/data_label_format/) | ส่งคืนรูปแบบป้ายข้อมูล.<br/>            อ่านอย่างเดียว [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/th/aspose.slides.charts/datalabel/value_from_cell/) | รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก. ใช้ถ้า property IDataLabelFormat.ShowLabelValueFromCell มีค่า true. |
| [`label_shape_type`](/slides/python-net/th/aspose.slides.charts/datalabel/label_shape_type/) | รับหรือกำหนดประเภทรูปทรงของป้ายข้อมูล.<br/>             ส่งคืน [`ShapeType.NOT_DEFINED`](/slides/python-net/th/aspose.slides/shapetype/NOT_DEFINED) หากไม่มีการกำหนดรูปทรง. |
| [`actual_x`](/slides/python-net/th/aspose.slides.charts/datalabel/actual_x/) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ.<br/>            เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าสิ่งที่เป็นจริง. <br/>            อ่าน **float**. |
| [`actual_y`](/slides/python-net/th/aspose.slides.charts/datalabel/actual_y/) | ระบุตำแหน่งด้านบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ.<br/>            เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าสิ่งที่เป็นจริง. <br/>            อ่าน **float**. |
| [`actual_width`](/slides/python-net/th/aspose.slides.charts/datalabel/actual_width/) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. <br/>            อ่าน **float**. |
| [`actual_height`](/slides/python-net/th/aspose.slides.charts/datalabel/actual_height/) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. <br/>            อ่าน **float**. |
| [`slide`](/slides/python-net/th/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/datalabel/presentation/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/th/aspose.slides.charts/datalabel/hide/#) | ทำให้ป้ายข้อมูลถูกซ่อนโดยตั้งค่าทุกแฟล็ก Show*-flags (ShowValue, ...) เป็นสถานะ false.<br/>            IsVisible จะเป็น false หลังจากนี้. |
| [`get_actual_label_text(self)`](/slides/python-net/th/aspose.slides.charts/datalabel/get_actual_label_text/#) | ส่งคืนข้อความป้ายจริงตามการตั้งค่า DataLabelFormat หรือค่า TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/th/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text".<br/>            หาก TextFrameForOverriding ได้รับการเริ่มต้นแล้วก็จะเปลี่ยนข้อความของมันเท่านั้น. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)