---
title: Trendline class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/trendline/
---
## คลาส Trendline

คลาสนี้แสดงเส้นแนวโน้มของชุดข้อมูลแผนภูมิ

ประเภท Trendline เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`trendline_name`](/slides/python-net/th/aspose.slides.charts/trendline/trendline_name/) | รับหรือกำหนดชื่อของเส้นแนวโน้ม.<br/>            อ่าน/เขียน **str**. |
| [`trendline_type`](/slides/python-net/th/aspose.slides.charts/trendline/trendline_type/) | รับหรือกำหนดประเภทของเส้นแนวโน้ม.<br/>            อ่าน/เขียน [`TrendlineType`](/slides/python-net/th/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/th/aspose.slides.charts/trendline/format/) | แสดงรูปแบบของเส้นแนวโน้ม.<br/>            อ่าน/เขียน [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/th/aspose.slides.charts/trendline/backward/) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยบนแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายออกก่อนข้อมูลของซีรีส์ที่กำลังทำแนวโน้ม. ในแผนภูมิแบบกระจายและไม่ใช่แบบกระจาย ค่าใด ๆ ที่ไม่เป็นลบก็ได้.<br/>            อ่าน/เขียน **float**. |
| [`forward`](/slides/python-net/th/aspose.slides.charts/trendline/forward/) | ระบุจำนวนของหมวดหมู่ (หรือหน่วยบนแผนภูมิแบบกระจาย) ที่เส้นแนวโน้มขยายออกหลังข้อมูลของซีรีส์ที่กำลังทำแนวโน้ม. ในแผนภูมิแบบกระจายและไม่ใช่แบบกระจาย ค่าใด ๆ ที่ไม่เป็นลบก็ได้.<br/>            อ่าน/เขียน **float**. |
| [`intercept`](/slides/python-net/th/aspose.slides.charts/trendline/intercept/) | ระบุค่าที่เส้นแนวโน้มจะตัดแกน y. คุณสมบัตินี้สนับสนุนเฉพาะเมื่อประเภทเส้นแนวโน้มเป็น exp, linear หรือ poly.<br/>            อ่าน/เขียน **float**. |
| [`display_equation`](/slides/python-net/th/aspose.slides.charts/trendline/display_equation/) | ระบุว่าคสมการของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับค่า Rsquaredvalue).<br/>            อ่าน/เขียน **bool**. |
| [`order`](/slides/python-net/th/aspose.slides.charts/trendline/order/) | ระบุลำดับของเส้นแนวโน้มพหุนาม. จะถูกละเลยสำหรับประเภทเส้นแนวโน้มอื่น ๆ. ค่าต้องอยู่ระหว่าง 2 ถึง 6.<br/>            อ่าน/เขียน **int**. |
| [`period`](/slides/python-net/th/aspose.slides.charts/trendline/period/) | ระบุช่วงเวลาของเส้นแนวโน้มสำหรับเส้นแนวโน้มค่าเฉลี่ยเคลื่อนที่. จะถูกละเลยสำหรับรูปแบบเส้นแนวโน้มอื่น.<br/>            ค่าต้องอยู่ระหว่าง 2 ถึง 255.<br/>            อ่าน/เขียน **int**. |
| [`display_r_squared_value`](/slides/python-net/th/aspose.slides.charts/trendline/display_r_squared_value/) | ระบุว่าค่า R-squared ของเส้นแนวโน้มจะแสดงบนแผนภูมิ (ในป้ายกำกับเดียวกับสมการ).<br/>            อ่าน/เขียน **bool**. |
| [`related_legend_entry`](/slides/python-net/th/aspose.slides.charts/trendline/related_legend_entry/) | แสดงรายการคำอธิบายที่เกี่ยวข้องกับเส้นแนวโน้มนี้<br/>            อ่านอย่างเดียว [`ILegendEntryProperties`](/slides/python-net/th/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/th/aspose.slides.charts/trendline/text_frame_for_overriding/) | สามารถบรรจุข้อความที่จัดรูปแบบอย่างหลากหลาย. หากคุณสมบัตินี้ไม่เป็น None แล้วค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างอัตโนมัติของป้ายข้อมูล.<br/>            ข้อความที่สร้างอัตโนมัติของป้ายข้อมูลหมายถึงข้อความที่จัดการโดย ShowSeriesName, ShowValue, ... และจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/trendline/text_format/) | คืนค่ารูปแบบข้อความ.<br/>            อ่านอย่างเดียว [`IChartTextFormat`](/slides/python-net/th/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/trendline/chart/) | คืนค่าแผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/th/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/trendline/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/th/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text".<br/>            หาก TextFrameForOverriding ถูกเริ่มต้นแล้วจะทำการเปลี่ยนข้อความของมันเท่านั้น. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)