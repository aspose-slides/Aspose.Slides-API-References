---
title: DataLabelCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection คลาส

แสดงฉลากของชุดข้อมูล.

ชนิด DataLabelCollection เปิดให้เข้าถึงสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`chart`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/chart/) | ส่งคืนแผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/is_visible/) | False หมายความว่าป้ายข้อมูลจะไม่แสดงเป็นค่าเริ่มต้น (และดังนั้นทุก <br/>            Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false).<br/>            อ่านอย่างเดียว **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | รับจำนวนของป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`count`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/count/) | รับจำนวนของป้ายข้อมูลทั้งหมดในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`default_data_label_format`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/default_data_label_format/) | รับรูปแบบป้ายข้อมูลเริ่มต้น.<br/>            อ่านอย่างเดียว [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/leader_lines_format/) | เป็นรูปแบบของเส้นนำป้ายข้อมูล.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/parent_series/) | รับชุดข้อมูลแม่.<br/>            อ่านอย่างเดียว [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | รับหรือกำหนดประเภทรูปแบบเริ่มต้นสำหรับป้ายข้อมูล.<br/>             ส่งคืน [`ShapeType.NOT_DEFINED`](/slides/python-net/th/aspose.slides/shapetype/NOT_DEFINED) หากไม่มีการกำหนดรูปแบบ. |
| [`slide`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/presentation/) |  |

รับป้ายข้อมูลสำหรับจุดข้อมูลด้วยดัชนีที่ระบุ.

## ตัวชี้ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`hide(self)`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/hide/#) | ทำให้ป้ายข้อมูลถูกซ่อนเป็นค่าเริ่มต้นโดยตั้งค่า Show*-flags (ShowValue, ...) ทั้งหมดของ<br/>            คุณสมบัติ DefaultDataLabelFormat ให้เป็นสถานะ false.<br/>            IsVisible จะเป็น false หลังจากนี้. |
| [`index_of(self, value)`](/slides/python-net/th/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)