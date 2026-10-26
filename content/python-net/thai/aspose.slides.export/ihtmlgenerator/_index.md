---
title: IHtmlGenerator class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator class

เครื่องกำเนิด Html.

The IHtmlGenerator type exposes the following members:

## คุณสมบัติ

| Property | คำอธิบาย |
| :- | :- |
| [`slide_image_size`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Returns slide image size.<br/>            อ่านอย่างเดียว [`SizeF`](/slides/python-net/th/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Returns a unit in which slide image size is specified.<br/>            อ่านอย่างเดียว [`SvgCoordinateUnit`](/slides/python-net/th/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Returns a css code of unit in which slide image size is specified.<br/>            อ่านอย่างเดียว **str**. |
| [`previous_slide_index`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Returns index of previously rendered slide or -1 if first slide is rendering.<br/>            อ่านอย่างเดียว **int**. |
| [`slide_index`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/slide_index/) | Returns index of currently rendering slide.<br/>            อ่านอย่างเดียว **int**. |
| [`next_slide_index`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide.<br/>            อ่านอย่างเดียว **int**. |

## วิธีการ

| Method | คำอธิบาย |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_html/#str) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| [`add_html(self, html)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | เพิ่มข้อความ HTML ที่จัดรูปแบบแล้ว. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_text/#str) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี้ html.<br/>            ไม่แทนที่การขึ้นบรรทัดใหม่และช่องว่าง. |
| [`add_text(self, text)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี้ html.<br/>            ไม่แทนที่การขึ้นบรรทัดใหม่และช่องว่าง. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | เพิ่มข้อความธรรมดาไปยังไฟล์ html โดยแทนที่อักขระพิเศษด้วยเอนทิตี้ html.<br/>            ไม่แทนที่การขึ้นบรรทัดใหม่และช่องว่าง. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/th/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | อ้างอิงค่าแอตทริบิวต์และเพิ่มลงในไฟล์ html. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)