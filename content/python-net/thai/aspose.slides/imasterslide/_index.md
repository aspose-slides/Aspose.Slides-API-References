---
title: IMasterSlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/imasterslide/
---
## IMasterSlide คลาส

Represents a master slide in a presentation.

The IMasterSlide type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/imasterslide/header_footer_manager/) | คืนค่า HeaderFooter manager ของ master slide.<br/>            อ่านอย่างเดียว [`IMasterSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/th/aspose.slides/imasterslide/title_style/) | คืนค่า style ของข้อความหัวเรื่อง.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/th/aspose.slides/imasterslide/body_style/) | คืนค่า style ของข้อความเนื้อหา.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/th/aspose.slides/imasterslide/other_style/) | คืนค่า style ของข้อความอื่น.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/th/aspose.slides/imasterslide/layout_slides/) | คืนค่า collection ของ child layout slides สำหรับ master slide นี้.<br/>            อ่านอย่างเดียว [`IMasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/th/aspose.slides/imasterslide/preserve/) | กำหนดว่า master ที่สอดคล้องจะถูกลบเมื่อทุก <br/>            สไลด์ที่ตาม master นั้นถูกลบ.<br/>            หมายเหตุ: Aspose.Slides จะไม่ลบ master ที่ไม่ได้ใช้ใด ๆ ด้วยตนเอง, <br/>            เพื่อทำการลบ master ที่ไม่ได้ใช้จริงให้เรียก **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            อ่าน/เขียน **bool**. |
| [`has_depending_slides`](/slides/python-net/th/aspose.slides/imasterslide/has_depending_slides/) | คืนค่า true หากมีอย่างน้อยหนึ่งสไลด์ที่พึ่งพา master slide นี้.<br/>            อ่านอย่างเดียว **bool**. |
| [`drawing_guides`](/slides/python-net/th/aspose.slides/imasterslide/drawing_guides/) | คืนค่า collection ของ drawing guides สำหรับ master slide.<br/>            อ่านอย่างเดียว [`IDrawingGuidesCollection`](/slides/python-net/th/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/th/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/th/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/th/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/th/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/th/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/th/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/th/aspose.slides/imasterslide/theme_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/th/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | สร้าง master slide ใหม่โดยอิงจาก master slide ปัจจุบัน, ใช้ธีมภายนอกกับมัน <br/>            และนำ master slide ที่สร้างไปใช้กับสไลด์ที่พึ่งพาทั้งหมด. |
| [`get_depending_slides(self)`](/slides/python-net/th/aspose.slides/imasterslide/get_depending_slides/#) | คืนค่า array ที่มีสไลด์ทั้งหมดที่พึ่งพา master slide นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/imasterslide/create_theme_effective/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)