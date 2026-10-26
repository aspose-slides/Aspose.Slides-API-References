---
title: OleObjectFrame class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/oleobjectframe/
---
## OleObjectFrame คลาส

แสดงถึงอ็อบเจ็กต์ OLE บนสไลด์หนึ่ง.

**การสืบทอด:**[`OleObjectFrame`](/slides/python-net/th/aspose.slides/oleobjectframe) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

ประเภท OleObjectFrame เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/oleobjectframe/is_text_holder/) | กำหนดว่รูปร่างเป็น TextHolder_PPT หรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/oleobjectframe/placeholder/) | คืนค่า placeholder ของรูปร่าง. คืนค่า None หากรูปร่างไม่มี placeholder.<br/>            อ่านอย่างเดียว [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/oleobjectframe/custom_data/) | คืนค่าข้อมูลกำหนดเองของรูปร่าง.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/oleobjectframe/raw_frame/) | คืนค่าหรือกำหนดคุณสมบัติของกรอบรูปร่างดิบ.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/oleobjectframe/frame/) | คืนค่าหรือกำหนดคุณสมบัติของกรอบรูปร่าง.<br/>            อ่าน/เขียน [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/oleobjectframe/line_format/) | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปแบบบางรูปที่ไม่มีคุณสมบัติของเส้น.<br/>            อ่านอย่างเดียว [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/oleobjectframe/three_d_format/) | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปแบบบางรูปที่ไม่มีคุณสมบัติ 3 มิติ.<br/>            อ่านอย่างเดียว [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/oleobjectframe/effect_format/) | คืนค่าอ็อบเจ็กต์ EffectFormat ซึ่งมีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปแบบบางรูปที่ไม่มีคุณสมบัติเอฟเฟกต์.<br/>            อ่านอย่างเดียว [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/oleobjectframe/fill_format/) | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง.<br/>            หมายเหตุ: อาจคืนค่า None สำหรับรูปแบบบางรูปที่ไม่มีคุณสมบัติการเติม.<br/>            อ่านอย่างเดียว [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/oleobjectframe/hyperlink_click/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดไว้สำหรับการคลิกเมาส์.<br/>            อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/oleobjectframe/hyperlink_mouse_over/) | คืนค่าหรือกำหนด hyperlink ที่กำหนดไว้สำหรับการวางเมาส์.<br/>           อ่าน/เขียน [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/oleobjectframe/hyperlink_manager/) | คืนค่า hyperlink manager.<br/>            อ่านอย่างเดียว [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/oleobjectframe/hidden/) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/oleobjectframe/z_order_position/) | คืนตำแหน่งของรูปร่างในลำดับ z.<br/>            Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z.<br/>            อ่านอย่างเดียว **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/oleobjectframe/connection_site_count/) | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง.<br/>            อ่านอย่างเดียว **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/oleobjectframe/rotation/) | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา.<br/>            อ่าน/เขียน **float**. |
| [`x`](/slides/python-net/th/aspose.slides/oleobjectframe/x/) | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`y`](/slides/python-net/th/aspose.slides/oleobjectframe/y/) | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`width`](/slides/python-net/th/aspose.slides/oleobjectframe/width/) | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`height`](/slides/python-net/th/aspose.slides/oleobjectframe/height/) | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด.<br/>            อ่าน/เขียน **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/oleobjectframe/black_white_mode/) | คุณสมบัติกำหนดว่รูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว.<br/>            อ่าน/เขียน [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/oleobjectframe/unique_id/) | คืนค่า identifier ภายในที่กำหนดขอบเขตของงานนำเสนอเพื่อใช้โดย add-in หรือโค้ดอื่น.<br/>            เนื่องจากค่าตัวนี้สามารถถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/oleobjectframe/office_interop_shape_id/) | คืนค่า identifier ที่กำหนดขอบเขตของสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกที่ในเอกสาร.<br/>            อ่านอย่างเดียว **int**.<br/>            ดูเพิ่มเติม [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/oleobjectframe/alternative_text/) | คืนค่าหรือกำหนดข้อความแทน (alternative text) ที่เกี่ยวข้องกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/oleobjectframe/alternative_text_title/) | คืนค่าหรือกำหนดหัวข้อของข้อความแทนที่เกี่ยวข้องกับรูปร่าง.<br/>            อ่าน/เขียน **str**. |
| [`name`](/slides/python-net/th/aspose.slides/oleobjectframe/name/) | คืนค่าหรือกำหนดชื่อของรูปร่าง.<br/>            ต้องไม่เป็น None. หากต้องการใช้ค่าเป็นสตริงว่างให้ตั้งค่าเป็น ''.<br/>            อ่าน/เขียน **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/oleobjectframe/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            อ่าน/เขียน **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/oleobjectframe/shape_lock/) | คืนค่าการล็อคของรูปร่าง.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/oleobjectframe/is_grouped/) | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/oleobjectframe/parent_group/) | คืนค่าอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            อ่านอย่างเดียว [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/oleobjectframe/slide/) | คืนสไลด์พ่อแม่ของรูปร่าง.<br/>            อ่านอย่างเดียว [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/oleobjectframe/presentation/) | คืนงานนำเสนอพ่อแม่ของสไลด์.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/oleobjectframe/graphical_object_lock/) | คืนค่าการล็อคของรูปร่าง.<br/>            อ่านอย่างเดียว [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`substitute_picture_format`](/slides/python-net/th/aspose.slides/oleobjectframe/substitute_picture_format/) | คืนค่าอ็อบเจ็กต์คุณสมบัติการเติมภาพ OleObject.<br/>            อ่านอย่างเดียว [`IPictureFillFormat`](/slides/python-net/th/aspose.slides/ipicturefillformat). |
| [`substitute_picture_title`](/slides/python-net/th/aspose.slides/oleobjectframe/substitute_picture_title/) | คืนค่าหรือกำหนดหัวข้อสำหรับไอคอน OleObject.<br/>            อ่าน/เขียน **str**. |
| [`object_name`](/slides/python-net/th/aspose.slides/oleobjectframe/object_name/) | คืนค่าหรือกำหนดชื่อของอ็อบเจ็กต์.<br/>            อ่าน/เขียน **str**. |
| [`object_prog_id`](/slides/python-net/th/aspose.slides/oleobjectframe/object_prog_id/) | คืนค่า ProgID ของอ็อบเจ็กต์.<br/>            อ่านอย่างเดียว **str**. |
| [`link_file_name`](/slides/python-net/th/aspose.slides/oleobjectframe/link_file_name/) | คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์สั้น.<br/>            อ่านอย่างเดียว **str**. |
| [`link_path_long`](/slides/python-net/th/aspose.slides/oleobjectframe/link_path_long/) | คืนค่าเส้นทางเต็มของไฟล์ที่เชื่อมโยง. จะใช้ชื่อไฟล์ยาว.<br/>            อ่าน/เขียน **str**. |
| [`link_path_relative`](/slides/python-net/th/aspose.slides/oleobjectframe/link_path_relative/) | คืนค่าเส้นทางสัมพันธ์ของไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นคืนค่าสตริงว่าง.<br/>            อ่านอย่างเดียว **str**. |
| [`embedded_file_label`](/slides/python-net/th/aspose.slides/oleobjectframe/embedded_file_label/) | คืนค่าชื่อไฟล์ของอ็อบเจ็กต์ OLE ที่ฝังอยู่ |
| [`embedded_file_name`](/slides/python-net/th/aspose.slides/oleobjectframe/embedded_file_name/) | คืนค่าเส้นทางของอ็อบเจ็กต์ OLE ที่ฝังอยู่ |
| [`embedded_data`](/slides/python-net/th/aspose.slides/oleobjectframe/embedded_data/) | รับหรือกำหนดข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่.<br/>            อ่าน/เขียน [`IOleEmbeddedDataInfo`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo). |
| [`is_object_icon`](/slides/python-net/th/aspose.slides/oleobjectframe/is_object_icon/) | กำหนดว่าอ็อบเจ็กต์แสดงเป็นไอคอนไหม.<br/>            อ่าน/เขียน **bool**. |
| [`is_object_link`](/slides/python-net/th/aspose.slides/oleobjectframe/is_object_link/) | กำหนดว่าอ็อบเจ็กต์เชื่อมโยงกับไฟล์ภายนอกหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`update_automatic`](/slides/python-net/th/aspose.slides/oleobjectframe/update_automatic/) | กำหนดว่าตัวอ็อบเจ็กต์ที่ฝังและเชื่อมโยงจะอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์งานนำเสนอหรือไม่.<br/>            อ่าน/เขียน **bool**. |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/oleobjectframe/get_image/#) | คืนค่าภาพย่อของรูปร่าง.<br/>            ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/oleobjectframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของรูปร่าง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/oleobjectframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/oleobjectframe/remove_placeholder/#) | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/oleobjectframe/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/oleobjectframe/get_base_placeholder/#) | คืนค่า placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมาจาก).<br/>            จะคืนค่า None หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/oleobjectframe/get_visual_bounds/#) | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [`set_embedded_data(self, embedded_data)`](/slides/python-net/th/aspose.slides/oleobjectframe/set_embedded_data/#ioleembeddeddatainfo) | ตั้งค่าข้อมูลเกี่ยวกับข้อมูล OLE ที่ฝังอยู่.<br/>            <br/>            เมธอดนี้เปลี่ยนคุณสมบัติของอ็อบเจ็กต์ให้สอดคล้องกับข้อมูลใหม่และ <br/>            ตั้งค่า IsObjectLink flag เป็น false, แสดงว่าอ็อบเจ็กต์ OLE ถูกฝัง. |

### ดูเพิ่มเติม
* คลาส [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* คลาส [`OleObjectFrame`](/slides/python-net/th/aspose.slides/oleobjectframe)
* คลาส [`Shape`](/slides/python-net/th/aspose.slides/shape)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)