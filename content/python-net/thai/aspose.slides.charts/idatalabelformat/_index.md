---
title: IDataLabelFormat class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat คลาส

แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.

IDataLabelFormat type เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/) | อ่าน/เขียน **bool**. |
| [`number_format`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/number_format/) | แสดงสตริงรูปแบบสำหรับอ็อบเจกต์ DataLabels.<br/>            อ่าน/เขียน **str**. |
| [`format`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/format/) | แสดงรูปแบบของป้ายข้อมูล.<br/>            อ่านอย่างเดียว [`IFormat`](/slides/python-net/th/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/position/) | แสดงตำแหน่งของป้ายข้อมูล.<br/>            อ่าน/เขียน [`LegendDataLabelPosition`](/slides/python-net/th/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_legend_key/) | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True ถ้าคีย์คำอธิบายของป้ายข้อมูลมองเห็นได้.<br/>            อ่าน/เขียน **bool**. |
| [`show_value`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_value/) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True แสดงค่าร้อยละ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_category_name`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_category_name/) | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_series_name`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_series_name/) | คืนค่า หรือกำหนดค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อชุดข้อมูลสำหรับป้ายข้อมูลบนแผนภูมิ.<br/>            True เพื่อแสดงชื่อชุดข้อมูล. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_percentage`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_percentage/) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True แสดงค่าร้อยละ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_bubble_size`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_bubble_size/) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True แสดงค่าขนาดฟอง. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_leader_lines`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_leader_lines/) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True แสดงเส้นนำ. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็น data callout หรือเป็นป้ายข้อมูล.<br/>            <br/>            หากพาเรนต์ของอ็อบเจกต์ DataLabelFormat นี้เป็นคอลเลกชัน DataLabelCollection ของป้ายข้อมูลแล้วคุณสมบัตินี้จะรับหรือกำหนดค่าเริ่มต้นของคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลใหม่ในคอลเลกชัน DataLabelCollection.<br/>            ตั้งค่าคุณสมบัตินี้ด้วยค่าหนึ่งจะตั้งค่าค่านั้นให้กับคุณสมบัติ ShowLabelAsDataCallout สำหรับป้ายข้อมูลทั้งหมดในคอลเลกชัน DataLabelCollection<br/>            (เช่น "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" ทำให้ทุก DataLabels[i].ShowLabelAsDataCallout มีค่าเท่ากับ val). |
| [`show_label_value_from_cell`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/) | แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลสำหรับแผนภูมิที่ระบุ.<br/>            True แสดงค่าเซลล์. False เพื่อซ่อน.<br/>            อ่าน/เขียน **bool**. |
| [`separator`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/separator/) | ตั้งค่า หรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ.<br/>            อ่าน/เขียน **str**. |
| [`text_format`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/text_format/) |  |
| [`chart`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/chart/) |  |
| [`slide`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides.charts/idatalabelformat/presentation/) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)