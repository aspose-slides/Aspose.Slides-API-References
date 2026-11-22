---
title: IDataLabelCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection คลาส

เป็นการแทนชุดป้ายกำกับของซีรีส์

ประเภท IDataLabelCollection แสดงสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | คืนค่ารูปแบบเริ่มต้นของป้ายข้อมูลทั้งหมดในคอลเลกชัน.<br/>            อ่านอย่างเดียว [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | แทนรูปแบบเส้นนำของป้ายข้อมูล.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/is_visible/) | False หมายความว่าป้ายข้อมูลไม่แสดงโดยค่าเริ่มต้น (และดังนั้นทุก <br/>            ธง Show* (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false).<br/>            อ่านอย่างเดียว **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | รับจำนวนป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`count`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/count/) | รับจำนวนป้ายข้อมูลทั้งหมดในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`parent_series`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/parent_series/) | คืนค่าซีรีส์แผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | รับหรือกำหนดประเภทรูปร่างเริ่มต้นสำหรับป้ายข้อมูล.<br/>             คืนค่า [`ShapeType.NOT_DEFINED`](/slides/python-net/th/aspose.slides/shapetype/NOT_DEFINED) หากไม่มีการกำหนดรูปร่าง. |
| [`chart`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/presentation/) |  |

รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีระบุ

## ตัวชี้ดัชนี

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## วิธีการ

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/hide/#) | ทำให้ป้ายข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าธง Show* ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็นสถานะ false.<br/>            IsVisible จะเป็น false หลังจากนี้. |
| [`index_of(self, value)`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | คืนค่าดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)