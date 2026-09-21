---
title: GraphicalObject class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/graphicalobject/
---
## คลาส GraphicalObject

แทนวัตถุกราฟิกเชิงนามธรรม

**Inheritance:**[`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท GraphicalObject มีสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/graphicalobject/is_text_holder/) | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/graphicalobject/placeholder/) | ส่งคืน placeholder ของรูปร่าง หากรูปร่างไม่มี placeholder จะส่งคืน None<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/graphicalobject/custom_data/) | ส่งคืนข้อมูลกำหนดเองของรูปร่าง<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/graphicalobject/raw_frame/) | รับหรือกำหนดคุณสมบัติของกรอบรูปร่างดิบ<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/graphicalobject/frame/) | รับหรือกำหนดคุณสมบัติของกรอบรูปร่าง<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/graphicalobject/line_format/) | ส่งคืนอ็อบเจ็กต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการจัดรูปแบบเส้น<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/graphicalobject/three_d_format/) | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่บรรจุคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปร่าง<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3D<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/graphicalobject/effect_format/) | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/graphicalobject/fill_format/) | ส่งคืนอ็อบเจ็กต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีสำหรับรูปร่าง<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/graphicalobject/hyperlink_click/) | รับหรือกำหนดลิงก์ที่กำหนดสำหรับการคลิกเมาส์<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/graphicalobject/hyperlink_mouse_over/) | รับหรือกำหนดลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/graphicalobject/hyperlink_manager/) | ส่งคืนผู้จัดการลิงก์<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/graphicalobject/hidden/) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/graphicalobject/z_order_position/) | ส่งคืนตำแหน่งของรูปร่างในลำดับ z-order<br/>            Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังสุดของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้าสุดของ z-order<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/graphicalobject/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/graphicalobject/rotation/) | รับหรือกำหนดจำนวนองศาที่รูปร่างกำหนดหมุนรอบแกน z<br/>            ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/graphicalobject/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง (หน่วยเป็น points)<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/graphicalobject/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง (หน่วยเป็น points)<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/graphicalobject/width/) | รับหรือกำหนดความกว้างของรูปร่าง (หน่วยเป็น points)<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/graphicalobject/height/) | รับหรือกำหนดความสูงของรูปร่าง (หน่วยเป็น points)<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/graphicalobject/black_white_mode/) | คุณสมบัติกำหนดว่ารูปร่างจะถูกเรนเดอร์ในโหมดแสดงผลขาว-ดำอย่างไร<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/graphicalobject/unique_id/) | ส่งคืนตัวระบุภายในที่ใช้ในระดับการนำเสนอ ซึ่งออกแบบมาสำหรับส่วนเสริมหรือโค้ดอื่น<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงต้องไม่ถือเป็นคีย์ที่คงที่และเป็นเอกลักษณ์<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/graphicalobject/office_interop_shape_id/) | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ในระดับสไลด์ ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้จากทุกที่ในเอกสาร<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/graphicalobject/alternative_text/) | รับหรือกำหนดข้อความแทนที่สัมพันธ์กับรูปร่าง<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/graphicalobject/alternative_text_title/) | รับหรือกำหนดหัวข้อของข้อความแทนที่สัมพันธ์กับรูปร่าง<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/graphicalobject/name/) | รับหรือกำหนดชื่อของรูปร่าง<br/>            ต้องไม่เป็น None หากต้องการให้เป็นค่าว่างให้ใช้สตริงเปล่า<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/graphicalobject/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/graphicalobject/shape_lock/) | ส่งคืนการล็อกของรูปร่าง<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/graphicalobject/is_grouped/) | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/graphicalobject/parent_group/) | ส่งคืนอ็อบเจ็กต์ GroupShape พาเรนต์หากรูปร่างอยู่ในกลุ่ม มิฉะนั้นจะคืนค่า None<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/graphicalobject/slide/) | ส่งคืนสไลด์พาเรนต์ของรูปร่าง<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/graphicalobject/presentation/) | ส่งคืนการนำเสนอพาเรนต์ของสไลด์<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/graphicalobject/graphical_object_lock/) | ส่งคืนการล็อกของรูปร่าง<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/graphicalobject/get_image/#) | ส่งคืนภาพย่อของรูปร่าง<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/graphicalobject/get_image/#shapethumbnailbounds-float-float) | ส่งคืนภาพย่อของรูปร่าง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/graphicalobject/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/graphicalobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/graphicalobject/remove_placeholder/#) | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/graphicalobject/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ไปยังที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/graphicalobject/get_base_placeholder/#) | ส่งคืนรูปร่าง placeholder พื้นฐาน (รูปร่างจาก layout หรือ master slide ที่รูปร่างปัจจุบันสืบทอดมาจาก) <br/>            จะคืนค่า None หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/graphicalobject/get_visual_bounds/#) | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |


### ดูเพิ่มเติม
* class [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)