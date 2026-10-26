---
title: SummaryZoomSection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection คลาส

Represents a Summary Zoom Section object in a Summary Zoom frame.

**การสืบทอด:**[`SummaryZoomSection`](/slides/python-net/th/aspose.slides/summaryzoomsection) → [`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

The SummaryZoomSection type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/summaryzoomsection/is_text_holder/) | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/summaryzoomsection/placeholder/) | คืนค่า placeholder สำหรับรูปร่าง. คืนค่า None หากรูปร่างไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/summaryzoomsection/custom_data/) | คืนค่าข้อมูลกำหนดเองของรูปร่าง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/summaryzoomsection/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติเฟรมดิบของรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/summaryzoomsection/frame/) | คืนค่า หรือกำหนดคุณสมบัติเฟรมของรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/summaryzoomsection/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่บรรจุตัวเลือกการกำหนดรูปแบบเส้นสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/summaryzoomsection/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟ็กต์ 3 มิติสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/summaryzoomsection/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟ็กต์พิกเซลที่ใช้กับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/summaryzoomsection/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่บรรจุตัวเลือกการกำหนดรูปแบบการเติมสีสำหรับรูปร่าง.<br/>            หมายเหตุ: สามารถคืนค่า None สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/summaryzoomsection/hyperlink_click/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/summaryzoomsection/hyperlink_mouse_over/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/summaryzoomsection/hyperlink_manager/) | คืนค่าไฮเปอร์ลิงก์ผู้จัดการ.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/summaryzoomsection/hidden/) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/summaryzoomsection/z_order_position/) | คืนค่าตำแหน่งของรูปร่างในลำดับ z-order.<br/>            Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้าของ z-order.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/summaryzoomsection/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/summaryzoomsection/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/summaryzoomsection/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/summaryzoomsection/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/summaryzoomsection/width/) | รับหรือกำหนดความกว้างของรูปร่าง, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/summaryzoomsection/height/) | รับหรือกำหนดความสูงของรูปร่าง, มีหน่วยเป็น points.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/summaryzoomsection/black_white_mode/) | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ.<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/summaryzoomsection/unique_id/) | คืนค่าอีดีดิภายในที่มีขอบเขตระดับการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-ins หรือโค้ดอื่น ๆ.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม มันไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/summaryzoomsection/office_interop_shape_id/) | คืนค่าอีดีเดียลที่มีขอบเขตระดับสไลด์และคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/summaryzoomsection/alternative_text/) | คืนค่า หรือกำหนดข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/summaryzoomsection/alternative_text_title/) | คืนค่า หรือกำหนดชื่อของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/summaryzoomsection/name/) | คืนค่า หรือกำหนดชื่อของรูปร่าง.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากต้องการ.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/summaryzoomsection/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/summaryzoomsection/shape_lock/) | คืนค่าการล็อกของรูปร่าง.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/summaryzoomsection/is_grouped/) | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/summaryzoomsection/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/summaryzoomsection/slide/) | คืนค่า สไลด์พ่อแม่ของรูปร่าง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/summaryzoomsection/presentation/) | คืนค่า การนำเสนอพ่อแม่ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/summaryzoomsection/graphical_object_lock/) | คืนค่าการล็อกของรูปร่าง.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/th/aspose.slides/summaryzoomsection/image_type/) | รับหรือกำหนดประเภทภาพของวัตถุ zoom.<br/>            อ่าน/เขียน [`ZoomImageType`](/slides/python-net/th/aspose.slides/zoomimagetype).<br/>            ค่าเริ่มต้น: Preview |
| [`return_to_parent`](/slides/python-net/th/aspose.slides/summaryzoomsection/return_to_parent/) | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้น: false |
| [`show_background`](/slides/python-net/th/aspose.slides/summaryzoomsection/show_background/) | รับหรือกำหนดค่าว่าการ Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่.<br/>            อ่าน/เขียน **bool**.<br/>            ค่าเริ่มต้น: true |
| [`zoom_image`](/slides/python-net/th/aspose.slides/summaryzoomsection/zoom_image/) | รับหรือกำหนดภาพสำหรับวัตถุ zoom.<br/>            อ่าน/เขียน [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/th/aspose.slides/summaryzoomsection/transition_duration/) | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์.<br/>            อ่าน/เขียน **float**.<br/>            ค่าเริ่มต้น: 1.0f |
| [`target_section`](/slides/python-net/th/aspose.slides/summaryzoomsection/target_section/) | รับหรือกำหนดอ็อบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงถึง.<br/>            อ่าน/เขียน [`ISection`](/slides/python-net/th/aspose.slides/isection). |
| [`title`](/slides/python-net/th/aspose.slides/summaryzoomsection/title/) | คืนค่าชื่อข้อความของอ็อบเจ็กต์ Summary Zoom Section. |
| [`description`](/slides/python-net/th/aspose.slides/summaryzoomsection/description/) | คืนค่าคำอธิบายข้อความของอ็อบเจ็กต์ Summary Zoom Section. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/summaryzoomsection/get_image/#) | คืนค่าภาพย่อของรูปร่าง.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/summaryzoomsection/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของรูปร่าง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/summaryzoomsection/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/summaryzoomsection/remove_placeholder/#) | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/summaryzoomsection/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/summaryzoomsection/get_base_placeholder/#) | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมา).<br/>            คืนค่า None หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/summaryzoomsection/get_visual_bounds/#) | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`SummaryZoomSection`](/slides/python-net/th/aspose.slides/summaryzoomsection)
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)