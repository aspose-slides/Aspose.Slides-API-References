---
title: IAutoShape class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iautoshape/
---
## IAutoShape คลาส

แทน AutoShape.

ประเภท IAutoShape เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/th/aspose.slides/iautoshape/shape_lock/) | คืนค่าการล็อกของรูปร่าง.<br/>            อ่านอย่างเดียว [`IAutoShapeLock`](/slides/python-net/th/aspose.slides/iautoshapelock). |
| [`auto_shape_lock`](/slides/python-net/th/aspose.slides/iautoshape/auto_shape_lock/) | คืนค่าการล็อกของ AutoShape.<br/>            อ่านอย่างเดียว [`IAutoShapeLock`](/slides/python-net/th/aspose.slides/iautoshapelock). |
| [`text_frame`](/slides/python-net/th/aspose.slides/iautoshape/text_frame/) | คืนค่าออบเจ็กต์ TextFrame สำหรับ AutoShape.<br/>            อ่านอย่างเดียว [`ITextFrame`](/slides/python-net/th/aspose.slides/itextframe). |
| [`use_background_fill`](/slides/python-net/th/aspose.slides/iautoshape/use_background_fill/) | กำหนดว่า autoshape นี้ควรเติมด้วยพื้นหลังของสไลด์แทนที่จะกำหนดโดยสไตล์หรือรูปแบบการเติม.<br/>            อ่าน/เขียน **bool**. |
| [`is_text_box`](/slides/python-net/th/aspose.slides/iautoshape/is_text_box/) | ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่. |
| [`shape_style`](/slides/python-net/th/aspose.slides/iautoshape/shape_style/) |  |
| [`shape_type`](/slides/python-net/th/aspose.slides/iautoshape/shape_type/) |  |
| [`adjustments`](/slides/python-net/th/aspose.slides/iautoshape/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/iautoshape/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides/iautoshape/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/iautoshape/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides/iautoshape/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides/iautoshape/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides/iautoshape/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides/iautoshape/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/iautoshape/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/iautoshape/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides/iautoshape/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides/iautoshape/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/iautoshape/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides/iautoshape/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides/iautoshape/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides/iautoshape/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides/iautoshape/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides/iautoshape/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides/iautoshape/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/iautoshape/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides/iautoshape/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides/iautoshape/is_decorative/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides/iautoshape/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/iautoshape/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides/iautoshape/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/iautoshape/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides/iautoshape/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/iautoshape/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/iautoshape/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/iautoshape/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/iautoshape/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/iautoshape/hyperlink_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/iautoshape/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/iautoshape/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/iautoshape/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/iautoshape/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`add_text_frame(self, text)`](/slides/python-net/th/aspose.slides/iautoshape/add_text_frame/#str) | เพิ่ม TextFrame ใหม่ให้กับรูปร่าง.<br/>            หากรูปร่างมี TextFrame อยู่แล้วก็จะเปลี่ยนข้อความของมันเท่านั้น. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/iautoshape/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/iautoshape/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/iautoshape/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/iautoshape/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/iautoshape/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/iautoshape/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/iautoshape/get_base_placeholder/#) |  |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)