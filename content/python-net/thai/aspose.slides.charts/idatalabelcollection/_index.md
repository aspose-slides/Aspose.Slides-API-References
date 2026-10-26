---
title: IDataLabelCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection คลาส

Represents a series labels.

The IDataLabelCollection type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | ส่งคืนรูปแบบเริ่มต้นของป้ายข้อมูลทั้งหมดในคอลเลกชัน.<br/>            อ่านอย่างเดียว [`IDataLabelFormat`](/slides/python-net/th/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | แสดงรูปแบบเส้นนำของป้ายข้อมูล.<br/>             อ่านอย่างเดียว [`IChartLinesFormat`](/slides/python-net/th/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/is_visible/) | False หมายความว่าป้ายข้อมูลจะไม่แสดงโดยค่าเริ่มต้น (และดังนั้น flag Show* ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false).<br/>            อ่านอย่างเดียว **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | รับจำนวนป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`count`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/count/) | รับจำนวนป้ายข้อมูลทั้งหมดในคอลเลกชัน.<br/>            อ่านอย่างเดียว **int**. |
| [`parent_series`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/parent_series/) | ส่งคืนซีรีส์แผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChartSeries`](/slides/python-net/th/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/presentation/) |  |

รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ.

## ดัชนี

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/hide/#) | ทำให้ป้ายข้อมูลถูกซ่อนโดยค่าเริ่มต้นโดยตั้งค่า flag Show* ทั้งหมด (ShowValue, ...) ของ<br/>            คุณสมบัติ DefaultDataLabelFormat ให้เป็นสถานะ false.<br/>            IsVisible จะเป็น false หลังจากนี้. |
| [`index_of(self, value)`](/slides/python-net/th/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)