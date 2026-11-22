---
title: IDataLabel class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/idatalabel/
---
## IDataLabel คลาส

เป็นตัวแทนของป้ายกำกับของชุดข้อมูล.

ประเภท IDataLabel เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/idatalabel/is_visible/) | False หมายความว่าป้ายกำกับข้อมูลไม่แสดง (และดังนั้นทุก Show*-flags (ShowValue, ...) จะเป็น false).<br/>            อ่านอย่างเดียว **bool**. |
| [`data_label_format`](/slides/python-net/th/aspose.slides.charts/idatalabel/data_label_format/) | คืนค่าฟอร์แมตของป้ายกำกับข้อมูล.<br/>            อ่านอย่างเดียว [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/th/aspose.slides.charts/idatalabel/value_from_cell/) | รับหรือกำหนดเซลล์ข้อมูลของ workbook. ใช้เมื่อคุณสมบัติ IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true. |
| [`label_shape_type`](/slides/python-net/th/aspose.slides.charts/idatalabel/label_shape_type/) | รับหรือกำหนดประเภทรูปร่างของป้ายกำกับข้อมูล.<br/>             คืนค่า [`ShapeType.NOT_DEFINED`](/slides/python-net/th/aspose.slides/shapetype/NOT_DEFINED) หากไม่มีการกำหนดรูปร่าง. |
| [`x`](/slides/python-net/th/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/th/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/th/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/th/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/th/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/th/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/th/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/th/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/th/aspose.slides.charts/idatalabel/actual_height/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/th/aspose.slides.charts/idatalabel/hide/#) | ทำให้ป้ายกำกับข้อมูลถูกซ่อนโดยตั้งค่าทุก Show*-flags (ShowValue, ...) เป็นสถานะ false.<br/>            IsVisible จะเป็น false หลังจากนี้. |
| [`get_actual_label_text(self)`](/slides/python-net/th/aspose.slides.charts/idatalabel/get_actual_label_text/#) | คืนข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่าของ TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/th/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)