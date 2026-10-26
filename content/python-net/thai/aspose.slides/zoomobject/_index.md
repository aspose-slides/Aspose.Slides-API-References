---
title: ZoomObject class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/zoomobject/
---
## คลาส ZoomObject

เป็นตัวแทนของ Zoom object ในสไลด์

**Inheritance:**[`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ZoomObject type เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/zoomobject/is_text_holder/) | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/zoomobject/placeholder/) | คืนค่า placeholder สำหรับ shape. คืนค่า None หาก shape ไม่มี placeholder.<br/>            Read-only [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/zoomobject/custom_data/) | คืนค่าข้อมูล custom ของ shape.<br/>            Read-only [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/zoomobject/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติของ raw shape frame.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/zoomobject/frame/) | คืนค่าหรือกำหนดคุณสมบัติของ shape frame.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/zoomobject/line_format/) | คืนค่าออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติของเส้น.<br/>            Read-only [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/zoomobject/three_d_format/) | คืนค่าออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติ 3d.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/zoomobject/effect_format/) | คืนค่าออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่นำไปใช้กับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            Read-only [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/zoomobject/fill_format/) | คืนค่าออบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับ shape ประเภทบางชนิดที่ไม่มีคุณสมบัติการเติม.<br/>            Read-only [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/zoomobject/hyperlink_click/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/zoomobject/hyperlink_mouse_over/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือ.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/zoomobject/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/zoomobject/hidden/) | กำหนดว่า shape ถูกซ่อนหรือไม่.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/zoomobject/z_order_position/) | คืนค่าตำแหน่งของ shape ใน z-order.<br/>            Shapes[0] คืนค่า shape ที่ตำแหน่งหลังสุดของ z-order,<br/>            และ Shapes[Shapes.Count - 1] คืนค่า shape ที่ตำแหน่งหน้าสุดของ z-order.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/zoomobject/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบน shape.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/zoomobject/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/th/aspose.slides/zoomobject/x/) | รับหรือกำหนดค่าพิกัด x ของมุมบนซ้ายของ shape, วัดเป็น points.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/th/aspose.slides/zoomobject/y/) | รับหรือกำหนดค่าพิกัด y ของมุมบนซ้ายของ shape, วัดเป็น points.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/th/aspose.slides/zoomobject/width/) | รับหรือกำหนดความกว้างของ shape, วัดเป็น points.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/th/aspose.slides/zoomobject/height/) | รับหรือกำหนดความสูงของ shape, วัดเป็น points.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/zoomobject/black_white_mode/) | คุณสมบัติกำหนดว่ารูปจะถูกแสดงอย่างไรในโหมดสีดำและสีขาว..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/zoomobject/unique_id/) | คืนค่า identifier ภายในที่กำหนดขอบเขตของงานนำเสนอเพื่อใช้โดย add-in หรือโค้ดอื่น.<br/>            เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            Read-only **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/zoomobject/office_interop_shape_id/) | คืนค่า identifier ที่มีขอบเขตของสไลด์ที่เป็นค่าเอกลักษณ์และคงที่ตลอดอายุของ shape และ<br/>            ให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้อย่างเชื่อถือจากทุกที่ในเอกสาร.<br/>            Read-only **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/zoomobject/alternative_text/) | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/zoomobject/alternative_text_title/) | คืนค่าหรือกำหนดหัวข้อความแทนที่เชื่อมโยงกับ shape.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/th/aspose.slides/zoomobject/name/) | คืนค่าหรือกำหนดชื่อของ shape.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างถ้าจำเป็น.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/zoomobject/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/zoomobject/shape_lock/) | คืนค่าการล็อกของ shape.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/zoomobject/is_grouped/) | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/zoomobject/parent_group/) | คืนค่าออบเจกต์ GroupShape พ่อแม่หาก shape ถูกจัดกลุ่ม. หากไม่เป็นเช่นนั้นคืนค่า None.<br/>            Read-only [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/zoomobject/slide/) | คืนค่าสไลด์พ่อแม่ของ shape.<br/>            Read-only [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/zoomobject/presentation/) | คืนค่างานนำเสนอพ่อแม่ของสไลด์.<br/>            Read-only [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/zoomobject/graphical_object_lock/) | คืนค่าการล็อกของ shape.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/th/aspose.slides/zoomobject/image_type/) | รับหรือกำหนดประเภทภาพของ zoom object.<br/>            Read/write [`ZoomImageType`](/slides/python-net/th/aspose.slides/zoomimagetype).<br/>            ค่าเริ่มต้น: Preview |
| [`return_to_parent`](/slides/python-net/th/aspose.slides/zoomobject/return_to_parent/) | รับหรือกำหนดพฤติกรรมการนำทางใน slideshow.<br/>            Read/write **bool**.<br/>            ค่าเริ่มต้น: false |
| [`show_background`](/slides/python-net/th/aspose.slides/zoomobject/show_background/) | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่.<br/>            Read/write **bool**.<br/>            ค่าเริ่มต้น: true |
| [`zoom_image`](/slides/python-net/th/aspose.slides/zoomobject/zoom_image/) | รับหรือกำหนดภาพสำหรับ zoom object.<br/>            Read/write [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/th/aspose.slides/zoomobject/transition_duration/) | รับหรือกำหนดระยะเวลาในการเปลี่ยนผ่านระหว่าง Zoom และสไลด์.<br/>            Read/write **float**.<br/>            ค่าเริ่มต้น: 1.0f |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/zoomobject/get_image/#) | คืนค่า thumbnail ของ shape.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type ถูกใช้โดยค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/zoomobject/get_image/#shapethumbnailbounds-float-float) | คืนค่า thumbnail ของ shape. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/zoomobject/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/zoomobject/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/zoomobject/remove_placeholder/#) | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/zoomobject/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นที่กำหนดไว้. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/zoomobject/get_base_placeholder/#) | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมา).<br/>            จะคืนค่า None หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/zoomobject/get_visual_bounds/#) | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่แสดงผล. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* คลาส [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)