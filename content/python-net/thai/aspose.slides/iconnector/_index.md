---
title: IConnector class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/iconnector/
---
## IConnector คลาส

แสดงถึงตัวเชื่อมต่อ.

ประเภท IConnector เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`shape_lock`](/slides/python-net/th/aspose.slides/iconnector/shape_lock/) | คืนค่าการล็อกของรูปทรง.<br/>            อ่านอย่างเดียว [`IConnectorLock`](/slides/python-net/th/aspose.slides/iconnectorlock). |
| [`connector_lock`](/slides/python-net/th/aspose.slides/iconnector/connector_lock/) | คืนค่าการล็อกของ Connector.<br/>            อ่านอย่างเดียว [`IConnectorLock`](/slides/python-net/th/aspose.slides/iconnectorlock). |
| [`start_shape_connected_to`](/slides/python-net/th/aspose.slides/iconnector/start_shape_connected_to/) | คืนค่าหรือกำหนดรูปทรงที่จะเชื่อมต่อส่วนเริ่มต้นของตัวเชื่อมต่อ.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`end_shape_connected_to`](/slides/python-net/th/aspose.slides/iconnector/end_shape_connected_to/) | คืนค่าหรือกำหนดรูปทรงที่จะเชื่อมต่อส่วนสุดท้ายของตัวเชื่อมต่อ.<br/>            อ่าน/เขียน [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`start_shape_connection_site_index`](/slides/python-net/th/aspose.slides/iconnector/start_shape_connection_site_index/) | คืนค่าหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปเริ่มต้น.<br/>            อ่าน/เขียน **int**. |
| [`end_shape_connection_site_index`](/slides/python-net/th/aspose.slides/iconnector/end_shape_connection_site_index/) | คืนค่าหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปสุดท้าย.<br/>            อ่าน/เขียน **int**. |
| [`shape_style`](/slides/python-net/th/aspose.slides/iconnector/shape_style/) |  |
| [`shape_type`](/slides/python-net/th/aspose.slides/iconnector/shape_type/) |  |
| [`adjustments`](/slides/python-net/th/aspose.slides/iconnector/adjustments/) |  |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/iconnector/is_text_holder/) |  |
| [`placeholder`](/slides/python-net/th/aspose.slides/iconnector/placeholder/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/iconnector/custom_data/) |  |
| [`raw_frame`](/slides/python-net/th/aspose.slides/iconnector/raw_frame/) |  |
| [`frame`](/slides/python-net/th/aspose.slides/iconnector/frame/) |  |
| [`line_format`](/slides/python-net/th/aspose.slides/iconnector/line_format/) |  |
| [`three_d_format`](/slides/python-net/th/aspose.slides/iconnector/three_d_format/) |  |
| [`effect_format`](/slides/python-net/th/aspose.slides/iconnector/effect_format/) |  |
| [`fill_format`](/slides/python-net/th/aspose.slides/iconnector/fill_format/) |  |
| [`hidden`](/slides/python-net/th/aspose.slides/iconnector/hidden/) |  |
| [`z_order_position`](/slides/python-net/th/aspose.slides/iconnector/z_order_position/) |  |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/iconnector/connection_site_count/) |  |
| [`rotation`](/slides/python-net/th/aspose.slides/iconnector/rotation/) |  |
| [`x`](/slides/python-net/th/aspose.slides/iconnector/x/) |  |
| [`y`](/slides/python-net/th/aspose.slides/iconnector/y/) |  |
| [`width`](/slides/python-net/th/aspose.slides/iconnector/width/) |  |
| [`height`](/slides/python-net/th/aspose.slides/iconnector/height/) |  |
| [`alternative_text`](/slides/python-net/th/aspose.slides/iconnector/alternative_text/) |  |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/iconnector/alternative_text_title/) |  |
| [`name`](/slides/python-net/th/aspose.slides/iconnector/name/) |  |
| [`is_decorative`](/slides/python-net/th/aspose.slides/iconnector/is_decorative/) |  |
| [`unique_id`](/slides/python-net/th/aspose.slides/iconnector/unique_id/) |  |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/iconnector/office_interop_shape_id/) |  |
| [`is_grouped`](/slides/python-net/th/aspose.slides/iconnector/is_grouped/) |  |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/iconnector/black_white_mode/) |  |
| [`parent_group`](/slides/python-net/th/aspose.slides/iconnector/parent_group/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/iconnector/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/iconnector/presentation/) |  |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/iconnector/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/iconnector/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/iconnector/hyperlink_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/iconnector/get_image/#) |  |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/iconnector/get_image/#shapethumbnailbounds-float-float) |  |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/iconnector/write_as_svg/#iorawiobase) |  |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/iconnector/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) |  |
| [`reroute(self)`](/slides/python-net/th/aspose.slides/iconnector/reroute/#) | กำหนดเส้นทางใหม่ของตัวเชื่อมต่อเพื่อให้เดินในเส้นทางที่สั้นที่สุดระหว่างรูปที่เชื่อมต่อ. |
| [`get_geometry_paths(self)`](/slides/python-net/th/aspose.slides/iconnector/get_geometry_paths/#) |  |
| [`set_geometry_path(self, geometry_path)`](/slides/python-net/th/aspose.slides/iconnector/set_geometry_path/#igeometrypath) |  |
| [`set_geometry_paths(self, geometry_paths)`](/slides/python-net/th/aspose.slides/iconnector/set_geometry_paths/#listigeometrypath) |  |
| [`create_shape_elements(self)`](/slides/python-net/th/aspose.slides/iconnector/create_shape_elements/#) |  |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/iconnector/add_placeholder/#iplaceholder) |  |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/iconnector/remove_placeholder/#) |  |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/iconnector/get_base_placeholder/#) |  |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)