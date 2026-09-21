---
title: Ink class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.ink/ink/
---
## Ink คลาส

แทนวัตถุหมึกบนสไลด์.

**การสืบทอด:**[`Ink`](/slides/python-net/th/aspose.slides.ink/ink) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท Ink เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides.ink/ink/is_text_holder/) | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides.ink/ink/placeholder/) | ส่งคืนตัวยึดของรูปทรง หากรูปทรงไม่มีตัวยึดจะส่งคืน None.<br/>            Read-only [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides.ink/ink/custom_data/) | ส่งคืนข้อมูลกำหนดเองของรูปทรง.<br/>            Read-only [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides.ink/ink/raw_frame/) | ส่งคืนหรือกำหนดคุณสมบัติของโครงร่างดิบของรูปทรง.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides.ink/ink/frame/) | ส่งคืนหรือกำหนดคุณสมบัติของโครงร่างรูปทรง.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides.ink/ink/line_format/) | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติของเส้น.<br/>            Read-only [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides.ink/ink/three_d_format/) | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides.ink/ink/effect_format/) | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            Read-only [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides.ink/ink/fill_format/) | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการจัดรูปแบบเติมสีสำหรับรูปทรง.<br/>            หมายเหตุ: สามารถส่งคืน None สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี.<br/>            Read-only [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides.ink/ink/hyperlink_click/) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides.ink/ink/hyperlink_mouse_over/) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides.ink/ink/hyperlink_manager/) | ส่งคืนผู้จัดการไฮเปอร์ลิงก์.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides.ink/ink/hidden/) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides.ink/ink/z_order_position/) | ส่งคืนตำแหน่งของรูปทรงในลำดับ z.<br/>            Shapes[0] ส่งคืนรูปทรงที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] ส่งคืนรูปทรงที่อยู่ด้านหน้าของลำดับ z.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides.ink/ink/connection_site_count/) | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides.ink/ink/rotation/) | ส่งคืนหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/th/aspose.slides.ink/ink/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง, หน่วยเป็น point.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/th/aspose.slides.ink/ink/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง, หน่วยเป็น point.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/th/aspose.slides.ink/ink/width/) | รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็น point.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/th/aspose.slides.ink/ink/height/) | รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็น point.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides.ink/ink/black_white_mode/) | คุณสมบัติกำหนดว่ารูปทรงจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides.ink/ink/unique_id/) | ส่งคืนตัวระบุภายในที่จำกัดขอบเขตการนำเสนอซึ่งตั้งใจให้ใช้โดยส่วนเสริมหรือโค้ดอื่น.<br/>            เนื่องจากค่านี้สามารถกำหนดค่าใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันอย่างถาวร.<br/>            Read-only **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides.ink/ink/office_interop_shape_id/) | ส่งคืนตัวระบุที่ไม่ซ้ำกันซึ่งจำกัดขอบเขตสไลด์และคงที่ตลอดอายุของรูปทรงและ<br/>            ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากส่วนใดของเอกสารได้อย่างเชื่อถือ.<br/>            Read-only **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides.ink/ink/alternative_text/) | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides.ink/ink/alternative_text_title/) | ส่งคืนหรือกำหนดหัวเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/th/aspose.slides.ink/ink/name/) | ส่งคืนหรือกำหนดชื่อของรูปทรง.<br/>            ต้องไม่เป็น None. ใช้ค่าว่างหากจำเป็น.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides.ink/ink/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides.ink/ink/shape_lock/) | ส่งคืนล็อกของรูปทรง.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides.ink/ink/is_grouped/) | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides.ink/ink/parent_group/) | ส่งคืนวัตถุ GroupShape พ่อแม่ถ้ารูปทรงถูกจัดกลุ่ม. มิฉะนั้นจะส่งคืน None.<br/>            Read-only [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides.ink/ink/slide/) | ส่งคืนสไลด์แม่ของรูปทรง.<br/>            Read-only [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides.ink/ink/presentation/) | ส่งคืนการนำเสนอแม่ของสไลด์.<br/>            Read-only [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides.ink/ink/graphical_object_lock/) | ส่งคืนล็อกของรูปทรง.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`traces`](/slides/python-net/th/aspose.slides.ink/ink/traces/) | รับทุกร่องที่มีอยู่ในองค์ประกอบ IInk [`IInkTrace`](/slides/python-net/th/aspose.slides.ink/iinktrace).<br/>            Read-only. |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides.ink/ink/get_image/#) | ส่งคืนภาพย่อของรูปทรง.<br/>            ShapeThumbnailBounds.Shape ประเภทขอบเขตภาพย่อของรูปทรงจะถูกใช้เป็นค่าเริ่มต้น. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides.ink/ink/get_image/#shapethumbnailbounds-float-float) | ส่งคืนภาพย่อของรูปทรง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides.ink/ink/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides.ink/ink/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides.ink/ink/remove_placeholder/#) | กำหนดว่ารูปทรงนี้ไม่ใช่ตัวยึด. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides.ink/ink/add_placeholder/#iplaceholder) | เพิ่มตัวยึดใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวยึดให้เป็นอันที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides.ink/ink/get_base_placeholder/#) | ส่งคืนรูปทรงตัวยึดพื้นฐาน (รูปทรงจากเลเอาท์และ/หรือสไลด์ต้นแบบที่รูปทรงปัจจุบันสืบทอดมาจาก).<br/>            จะส่งคืน None หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides.ink/ink/get_visual_bounds/#) | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`register_ink_effect_image(effect_type, image)`](/slides/python-net/th/aspose.slides.ink/ink/register_ink_effect_image/#inkeffecttype-iimage) | ลงทะเบียนภาพในชุดภาพกำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก.<br/>            ภาพเหล่านี้จะถูกใช้เมื่อเรนเดอร์หมึกด้วยค่า [`InkEffectType`](/slides/python-net/th/aspose.slides.ink/inkeffecttype) เฉพาะ,<br/>            เช่น Galaxy, Rainbow เป็นต้น. โดยการให้ภาพของคุณเอง คุณสามารถควบคุมลักษณะของแต่ละเอฟเฟกต์หมึกได้. |
| [`unregister_ink_effect_image(effect_type)`](/slides/python-net/th/aspose.slides.ink/ink/unregister_ink_effect_image/#inkeffecttype) | ยกเลิกการลงทะเบียนภาพจากชุดภาพกำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก<br/>            ภาพที่เคยลงทะเบียนผ่าน **Aspose.Slides.Ink.Ink.RegisterInkEffectImage(Aspose.Slides.Ink.InkEffectType,Aspose.Slide**. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`Ink`](/slides/python-net/th/aspose.slides.ink/ink)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides.ink`](/slides/python-net/th/aspose.slides.ink)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)