---
title: ZoomFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/zoomframe/
---
## คลาส ZoomFrame

แสดงวัตถุ Slide Zoom ในสไลด์หนึ่ง

**การสืบทอด:**[`ZoomFrame`](/slides/python-net/th/aspose.slides/zoomframe) → [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท ZoomFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/zoomframe/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/zoomframe/placeholder/) | คืนค่าตัวแนบตำแหน่งสำหรับ shape. คืนค่า None หาก shape ไม่มีตัวแนบตำแหน่ง.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/zoomframe/custom_data/) | คืนค่าข้อมูลกำหนดเองของ shape.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/zoomframe/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape ดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/zoomframe/frame/) | คืนค่า หรือกำหนดคุณสมบัติของกรอบ shape.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/zoomframe/line_format/) | คืนค่าออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/zoomframe/three_d_format/) | คืนค่าออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติ 3d.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/zoomframe/effect_format/) | คืนค่าออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/zoomframe/fill_format/) | คืนค่าออบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติการเติม.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/zoomframe/hyperlink_click/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดไว้สำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/zoomframe/hyperlink_mouse_over/) | คืนค่า หรือกำหนด hyperlink ที่กำหนดไว้สำหรับการชี้เมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/zoomframe/hyperlink_manager/) | คืนค่าตัวจัดการ hyperlink.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/zoomframe/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/zoomframe/z_order_position/) | คืนค่าตำแหน่งของ shape ในลำดับ z-order.<br/>            Shapes[0] คืนค่า shape ที่อยู่ด้านหลังสุดของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าสุดของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/zoomframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/zoomframe/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/zoomframe/x/) | รับหรือกำหนดค่า x-coordinate ของมุมซ้ายบนของ shape, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/zoomframe/y/) | รับหรือกำหนดค่า y-coordinate ของมุมซ้ายบนของ shape, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/zoomframe/width/) | รับหรือกำหนดความกว้างของ shape, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/zoomframe/height/) | รับหรือกำหนดความสูงของ shape, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/zoomframe/black_white_mode/) | คุณสมบัติกำหนดว่า shape จะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ..<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/zoomframe/unique_id/) | คืนค่า identifier ภายในที่กำหนดตามการนำเสนอที่ใช้โดย add-in หรือโค้ดอื่น.<br/>            เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรพิจารณาเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/zoomframe/office_interop_shape_id/) | คืนค่า identifier ที่เป็นเอกลักษณ์ภายในสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากตำแหน่งใดก็ได้ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/zoomframe/alternative_text/) | คืนค่า หรือกำหนดข้อความอธิบายแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/zoomframe/alternative_text_title/) | คืนค่า หรือกำหนดหัวข้อของข้อความอธิบายแทนที่เชื่อมโยงกับ shape.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/zoomframe/name/) | คืนค่า หรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากต้องการ.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/zoomframe/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/zoomframe/shape_lock/) | คืนค่าการล็อกของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/zoomframe/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/zoomframe/parent_group/) | คืนค่าออบเจกต์ GroupShape พาเรนต์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/zoomframe/slide/) | คืนค่าสไลด์พาเรนต์ของ shape.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/zoomframe/presentation/) | คืนค่าการนำเสนอพาเรนต์ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/zoomframe/graphical_object_lock/) | คืนค่าการล็อกของ shape.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/th/aspose.slides/zoomframe/image_type/) | รับหรือกำหนดประเภทภาพของวัตถุ zoom.<br/>            อ่าน/เขียน [`ZoomImageType`](/slides/python-net/th/aspose.slides/zoomimagetype).<br/>            ค่าเริ่มต้น: Preview |
| [`return_to_parent`](/slides/python-net/th/aspose.slides/zoomframe/return_to_parent/) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้น: false |
| [`show_background`](/slides/python-net/th/aspose.slides/zoomframe/show_background/) | รับหรือกำหนดค่าว่าจะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้น: true |
| [`zoom_image`](/slides/python-net/th/aspose.slides/zoomframe/zoom_image/) | รับหรือกำหนดภาพสำหรับวัตถุ zoom.<br/>            อ่าน/เขียน [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/th/aspose.slides/zoomframe/transition_duration/) | รับหรือกำหนดระยะเวลาการเปลี่ยนจาก Zoom ไปยังสไลด์.<br/>            อ่าน/เขียน **float**.<br/>            ค่าเริ่มต้น: 1.0f |
| [`target_slide`](/slides/python-net/th/aspose.slides/zoomframe/target_slide/) | รับหรือกำหนดออบเจกต์สไลด์ที่วัตถุ Slide Zoom เชื่อมโยงถึง.<br/>            อ่าน/เขียน [`ISlide`](/slides/python-net/th/aspose.slides/islide). |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/zoomframe/get_image/#) | คืนค่าภาพย่อของ shape.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape shape thumbnail bounds โดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/zoomframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/zoomframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/zoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/zoomframe/remove_placeholder/#) | กำหนดว่ารูปนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/zoomframe/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นตามที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/zoomframe/get_base_placeholder/#) | คืนค่า placeholder shape พื้นฐาน (shape จากเค้าโครงการ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก).<br/>            คืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/zoomframe/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`ZoomFrame`](/slides/python-net/th/aspose.slides/zoomframe)
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)