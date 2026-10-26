---
title: DataLabelFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat คลาส

Represents formatting options for DataLabel.

**Inheritance:**[`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)

The DataLabelFormat type exposes the following members:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/th/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | อ่าน/เขียน **bool**. |
| [`number_format`](/slides/python-net/th/aspose.slides.charts/datalabelformat/number_format/) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels.<br/>            อ่าน/เขียน **str**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/datalabelformat/format/) | แสดงรูปแบบของป้ายข้อมูล.<br/>            อ่านอย่างเดียว [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/th/aspose.slides.charts/datalabelformat/position/) | แสดงตำแหน่งของป้ายข้อมูล.<br/>            อ่าน/เขียน [`LegendDataLabelPosition`](/slides/python-net/th/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_legend_key/) | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True หากคีย์คำอธิบายของป้ายข้อมูลมองเห็นได้.<br/>            อ่าน/เขียน **bool**. |
| [`show_value`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_value/) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True แสดงค่าร้อยละ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_category_name`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_category_name/) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_series_name`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_series_name/) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ.<br/>            True เพื่อแสดงชื่อซีรีส์. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_percentage`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_percentage/) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True แสดงค่าร้อยละ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_bubble_size`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_bubble_size/) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True แสดงค่าขนาดฟอง. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_leader_lines`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_leader_lines/) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True แสดงเส้นนำ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | แสดงพฤติกรรมการแสดงค่าของเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ.<br/>            True แสดงค่าของเซลล์. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/th/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็น data callout หรือเป็นป้ายข้อมูล.<br/>            <br/>            หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้ว<br/>            คุณสมบัตินี้จะรับหรือกำหนดค่าตั้งต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่<br/>            ที่อยู่ในคอลเลกชัน DataLabelCollection.<br/>            การตั้งค่าสมบัตินี้ด้วยค่าจะยังตั้งค่าดังกล่าวให้กับคุณสมบัติ ShowLabelAsDataCallout<br/>            สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection<br/>            (เช่น "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" ทำให้<br/>            ทุก DataLabels[i].ShowLabelAsDataCallout มีค่าเท่ากับ val). |
| [`separator`](/slides/python-net/th/aspose.slides.charts/datalabelformat/separator/) | ตั้งค่าหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ.<br/>            อ่าน/เขียน **str**. |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/datalabelformat/text_format/) | คืนค่ารูปแบบข้อความของแผนภูมิ.<br/>            อ่านอย่างเดียว [`IChartTextFormat`](/slides/python-net/th/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/th/aspose.slides.charts/datalabelformat/chart/) | คืนค่าแผนภูมิ.<br/>            อ่านอย่างเดียว [`IChart`](/slides/python-net/th/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/th/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/datalabelformat/presentation/) |  |

### ดูเพิ่มเติม
* คลาส [`DataLabelFormat`](/slides/python-net/th/aspose.slides.charts/datalabelformat)
* คลาส [`PVIObject`](/slides/python-net/th/aspose.slides/pviobject)
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)