---
title: Table class
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/table/
---
## Table คลาส

แสดงถึงตารางบนสไลด์หนึ่ง

**การสืบทอด:**[`Table`](/slides/python-net/th/aspose.slides/table) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ชนิด Table เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/table/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/table/placeholder/) | คืนค่า placeholder สำหรับ shape คืนค่า None หาก shape ไม่มี placeholder<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/table/custom_data/) | คืนค่าข้อมูล custom ของ shape<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/table/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติกรอบ raw shape frame<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/table/frame/) | คืนค่าหรือกำหนดคุณสมบัติกรอบ shape frame<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/table/line_format/) | คืนค่าออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทที่ไม่มีคุณสมบัติเส้น<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/table/three_d_format/) | คืนค่าออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟค 3d สำหรับ shape<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทที่ไม่มีคุณสมบัติ 3d<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/table/effect_format/) | คืนค่าออบเจกต์ EffectFormat ที่มีเอฟเฟคพิกเซลที่ใช้กับ shape<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทที่ไม่มีคุณสมบัติเอฟเฟค<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/table/fill_format/) | คืนค่าออบเจกต์ TableFormat.FillFormat ที่บรรจุการจัดรูปแบบเติมสำหรับ Table<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/table/hyperlink_click/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเม้าส์<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/table/hyperlink_mouse_over/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการชี้เม้าส์เหนือ<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/table/hyperlink_manager/) | คืนค่าตัวจัดการ hyperlink<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/table/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/table/z_order_position/) | คืนค่าตำแหน่งของ shape ใน z-order<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/table/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/table/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่ shape ถูกหมุนรอบแกน z<br/>            ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/table/x/) | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็น points<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/table/y/) | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็น points<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/table/width/) | รับหรือกำหนดความกว้างของ shape หน่วยเป็น points<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/table/height/) | รับหรือกำหนดความสูงของ shape หน่วยเป็น points<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/table/black_white_mode/) | คุณสมบัติกำหนดวิธีการแสดง shape ในโหมดสีขาว-ดำ<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/table/unique_id/) | คืนค่า identifier ภายในที่มีขอบเขตการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-ins หรือโค้ดอื่น<br/>            เพราะค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ต้องไม่ถือว่าเป็นคีย์ที่เป็นเอกลักษณ์คงที่<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่ม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/table/office_interop_shape_id/) | คืนค่า identifier ที่มีขอบเขตสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape จากที่ใด ๆ ในเอกสารได้อย่างเชื่อถือได้<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่ม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/table/alternative_text/) | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/table/alternative_text_title/) | คืนค่าหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/table/name/) | คืนค่า หรือกำหนดชื่อของ shape<br/>            ต้องไม่เป็น None ใช้ค่าว่างเป็นสตริงหากต้องการ<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/table/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/table/shape_lock/) | คืนค่าการล็อกของ shape<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/table/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/table/parent_group/) | คืนค่าออบเจกต์ GroupShape พาเรนต์ถ้า shape ถูกจัดกลุ่ม มิฉะนั้นคืนค่า None<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/table/slide/) | คืนค่า slide พาเรนต์ของ shape<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/table/presentation/) | คืนค่าการนำเสนอพาเรนต์ของสไลด์<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/table/graphical_object_lock/) | คืนค่าการล็อกของ shape<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`rows`](/slides/python-net/th/aspose.slides/table/rows/) | คืนค่าการรวบรวมของแถว<br/>            อ่านอย่างเดียว [`IRowCollection`](/slides/python-net/th/aspose.slides/irowcollection). |
| [`columns`](/slides/python-net/th/aspose.slides/table/columns/) | คืนค่าการรวบรวมของคอลัมน์<br/>            อ่านอย่างเดียว [`IColumnCollection`](/slides/python-net/th/aspose.slides/icolumncollection). |
| [`table_format`](/slides/python-net/th/aspose.slides/table/table_format/) | คืนค่าออบเจกต์ TableFormat ที่บรรจุคุณสมบัติกำหนดรูปแบบของตารางนี้<br/>            อ่านอย่างเดียว [`ITableFormat`](/slides/python-net/th/aspose.slides/itableformat). |
| [`style_preset`](/slides/python-net/th/aspose.slides/table/style_preset/) | รับหรือกำหนดสไตล์ตารางพื้นฐาน<br/>            อ่าน/เขียน [`TableStylePreset`](/slides/python-net/th/aspose.slides/tablestylepreset). |
| [`right_to_left`](/slides/python-net/th/aspose.slides/table/right_to_left/) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`first_row`](/slides/python-net/th/aspose.slides/table/first_row/) | กำหนดว่าขอบแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`first_col`](/slides/python-net/th/aspose.slides/table/first_col/) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`last_row`](/slides/python-net/th/aspose.slides/table/last_row/) | กำหนดว่าขอบสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`last_col`](/slides/python-net/th/aspose.slides/table/last_col/) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`horizontal_banding`](/slides/python-net/th/aspose.slides/table/horizontal_banding/) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`vertical_banding`](/slides/python-net/th/aspose.slides/table/vertical_banding/) | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่<br/>            อ่าน/เขียน **bool**. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/table/get_image/#) | คืนค่าภาพย่อของ shape<br/>            ใช้ ShapeThumbnailBounds.Shape shape thumbnail bounds type เป็นค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/table/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/table/write_as_svg/#iorawiobase) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/table/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |
| [`set_text_format(self, source)`](/slides/python-net/th/aspose.slides/table/set_text_format/#iportionformat) | กำหนดคุณสมบัติ format ของ portion ที่กำหนดให้กับ portion ทั้งหมดของเซลล์ตาราง. |
| [`set_text_format(self, source)`](/slides/python-net/th/aspose.slides/table/set_text_format/#iparagraphformat) | กำหนดคุณสมบัติ format ของ paragraph ที่กำหนดให้กับ paragraph ทั้งหมดของเซลล์ตาราง. |
| [`set_text_format(self, source)`](/slides/python-net/th/aspose.slides/table/set_text_format/#itextframeformat) | กำหนดคุณสมบัติ format ของ text frame ที่กำหนดให้กับ text frame ทั้งหมดของเซลล์ตาราง. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/table/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/table/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้กับออบเจกต์ที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/table/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมา)<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/table/get_visual_bounds/#) | รับกรอบที่มองเห็นได้ของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`merge_cells(self, cell1, cell2, allow_splitting)`](/slides/python-net/th/aspose.slides/table/merge_cells/#icell-icell-bool) | รวมเซลล์ที่อยู่ติดกัน. |


### ดูเพิ่มเติม
* class [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* class [`Table`](/slides/python-net/th/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)