---
title: ErrorBarsFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat คลาส

เป็นตัวแทนของแท่งความคลาดเคลื่อนของชุดข้อมูลแผนภูมิ. ค่าที่กำหนดเองของ ErrorBars อยู่ใน IChartDataPointCollection (ในคุณสมบัติ [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/error_bars_custom_values)).

ประเภท ErrorBarsFormat เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/type/) | รับหรือกำหนดประเภทของแท่งความคลาดเคลื่อน. <br/>            อ่าน/เขียน [`ErrorBarType`](/slides/python-net/th/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/value_type/) | เป็นตัวแทนของวิธีการที่เป็นไปได้ในการกำหนดความยาวของแท่งความคลาดเคลื่อน. <br/>            ในกรณีของประเภทค่าที่กำหนดเองเพื่อระบุค่า ให้ใช้คุณสมบัติ [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/th/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) ของจุดข้อมูลเฉพาะในคอลเลกชัน DataPoints ของชุดข้อมูล.<br/>            ในกรณีของประเภทค่า Fixed, Percentage หรือ StandardDeviation ให้ใช้คุณสมบัติ Value เพื่อระบุค่า.  <br/>            อ่าน/เขียน [`ErrorBarValueType`](/slides/python-net/th/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/has_end_cap/) | กำหนดว่าหัวปลายจะไม่ถูกวาดบนแท่งความคลาดเคลื่อน.<br/>            อ่าน/เขียน **bool**. |
| [`value`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/value/) | รับหรือกำหนดค่าที่ใช้ร่วมกับประเภทค่า Fixed, Percentage และ StandardDeviation เพื่อกำหนดความยาวของแท่งความคลาดเคลื่อน. <br/>            ในกรณีอื่น ๆ จะคืนค่า NaN.<br/>            อ่าน/เขียน **float**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/format/) | เป็นตัวแทนของรูปแบบของแท่งความคลาดเคลื่อน.<br/>            อ่าน/เขียน [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/chart/) | คืนแผนภูมิแม่.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/is_visible/) | รับหรือกำหนดการมองเห็นของ Error Bars.<br/>            อ่าน/เขียน **bool**. |
| [`slide`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/errorbarsformat/presentation/) |  |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)