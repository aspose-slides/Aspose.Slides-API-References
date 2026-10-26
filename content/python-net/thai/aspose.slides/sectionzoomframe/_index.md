---
title: SectionZoomFrame class
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame คลาส

Represents a Section Zoom object in a slide.

**Inheritance:**[`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe) → [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject) → [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject) → [`Shape`](/slides/python-net/th/aspose.slides/shape)

The SectionZoomFrame type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_text_holder`](/slides/python-net/th/aspose.slides/sectionzoomframe/is_text_holder/) | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่.<br/>            Read-only **bool**. |
| [`placeholder`](/slides/python-net/th/aspose.slides/sectionzoomframe/placeholder/) | คืนค่าตัวแทนของรูปทรง. คืนค่า None หากรูปทรงไม่มีตัวแทน.<br/>            Read-only [`IPlaceholder`](/slides/python-net/th/aspose.slides/iplaceholder). |
| [`custom_data`](/slides/python-net/th/aspose.slides/sectionzoomframe/custom_data/) | คืนค่าข้อมูลกำหนดเองของรูปทรง.<br/>            Read-only [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`raw_frame`](/slides/python-net/th/aspose.slides/sectionzoomframe/raw_frame/) | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`frame`](/slides/python-net/th/aspose.slides/sectionzoomframe/frame/) | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปทรง.<br/>            Read/write [`IShapeFrame`](/slides/python-net/th/aspose.slides/ishapeframe). |
| [`line_format`](/slides/python-net/th/aspose.slides/sectionzoomframe/line_format/) | คืนค่าออบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง.<br/>            Note: can return None for certain types of shapes which don't have line properties.<br/>            Read-only [`ILineFormat`](/slides/python-net/th/aspose.slides/ilineformat). |
| [`three_d_format`](/slides/python-net/th/aspose.slides/sectionzoomframe/three_d_format/) | คืนค่าออบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง.<br/>            Note: can return None for certain types of shapes which don't have 3d properties.<br/>            Read-only [`IThreeDFormat`](/slides/python-net/th/aspose.slides/ithreedformat). |
| [`effect_format`](/slides/python-net/th/aspose.slides/sectionzoomframe/effect_format/) | คืนค่าออบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง.<br/>            Note: can return None for certain types of shapes which don't have effect properties.<br/>            Read-only [`IEffectFormat`](/slides/python-net/th/aspose.slides/ieffectformat). |
| [`fill_format`](/slides/python-net/th/aspose.slides/sectionzoomframe/fill_format/) | คืนค่าออบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสำหรับรูปทรง.<br/>            Note: can return None for certain types of shapes which don't have fill properties.<br/>            Read-only [`IFillFormat`](/slides/python-net/th/aspose.slides/ifillformat). |
| [`hyperlink_click`](/slides/python-net/th/aspose.slides/sectionzoomframe/hyperlink_click/) | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/th/aspose.slides/sectionzoomframe/hyperlink_mouse_over/) | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการชี้เมาส์.<br/>            Read/write [`IHyperlink`](/slides/python-net/th/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/th/aspose.slides/sectionzoomframe/hyperlink_manager/) | คืนค่าตัวจัดการไฮเปอร์ลิงก์.<br/>            Read-only [`IHyperlinkManager`](/slides/python-net/th/aspose.slides/ihyperlinkmanager). |
| [`hidden`](/slides/python-net/th/aspose.slides/sectionzoomframe/hidden/) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่.<br/>            Read/write **bool**. |
| [`z_order_position`](/slides/python-net/th/aspose.slides/sectionzoomframe/z_order_position/) | คืนค่าตำแหน่งของรูปทรงในลำดับ z.<br/>            Shapes[0] คืนค่ารูปทรงที่อยู่ด้านหลังของลำดับ z,<br/>            และ Shapes[Shapes.Count - 1] คืนค่ารูปทรงที่อยู่ด้านหน้าของลำดับ z.<br/>            Read-only **int**. |
| [`connection_site_count`](/slides/python-net/th/aspose.slides/sectionzoomframe/connection_site_count/) | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง.<br/>            Read-only **int**. |
| [`rotation`](/slides/python-net/th/aspose.slides/sectionzoomframe/rotation/) | คืนค่า หรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z.<br/>            ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา.<br/>            Read/write **float**. |
| [`x`](/slides/python-net/th/aspose.slides/sectionzoomframe/x/) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง, มีหน่วยเป็นจุด.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/th/aspose.slides/sectionzoomframe/y/) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง, มีหน่วยเป็นจุด.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/th/aspose.slides/sectionzoomframe/width/) | รับหรือกำหนดความกว้างของรูปทรง, มีหน่วยเป็นจุด.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/th/aspose.slides/sectionzoomframe/height/) | รับหรือกำหนดความสูงของรูปทรง, มีหน่วยเป็นจุด.<br/>            Read/write **float**. |
| [`black_white_mode`](/slides/python-net/th/aspose.slides/sectionzoomframe/black_white_mode/) | คุณสมบัตินี้ระบุว่ารูปทรงจะแสดงผลแบบสีขาว-ดำอย่างไร..<br/>            Read/write [`BlackWhiteMode`](/slides/python-net/th/aspose.slides/blackwhitemode). |
| [`unique_id`](/slides/python-net/th/aspose.slides/sectionzoomframe/unique_id/) | คืนค่าอัจฉริยะภายในที่กำหนดขอบเขตการนำเสนอเพื่อใช้โดยแอดอินหรือโค้ดอื่น.<br/>            เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรใช้เป็นคีย์ที่ไม่เปลี่ยนแปลงอย่างถาวร.<br/>            Read-only **int**.<br/>            See also [`Shape.office_interop_shape_id`](/slides/python-net/th/aspose.slides/shape/office_interop_shape_id). |
| [`office_interop_shape_id`](/slides/python-net/th/aspose.slides/sectionzoomframe/office_interop_shape_id/) | คืนค่าอัจฉริยะที่กำหนดขอบเขตสไลด์ที่ไม่ซ้ำกันซึ่งคงที่ตลอดอายุของรูปทรงและ<br/>            ให้ PowerPoint หรือโค้ด interop อ้างอิงรูปทรงได้อย่างมั่นใจจากทุกส่วนของเอกสาร.<br/>            Read-only **int**.<br/>            See also [`Shape.unique_id`](/slides/python-net/th/aspose.slides/shape/unique_id). |
| [`alternative_text`](/slides/python-net/th/aspose.slides/sectionzoomframe/alternative_text/) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            Read/write **str**. |
| [`alternative_text_title`](/slides/python-net/th/aspose.slides/sectionzoomframe/alternative_text_title/) | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง.<br/>            Read/write **str**. |
| [`name`](/slides/python-net/th/aspose.slides/sectionzoomframe/name/) | คืนค่า หรือกำหนดชื่อของรูปทรง.<br/>            ต้องไม่เป็น None. ใช้ค่าเป็นสตริงว่างหากจำเป็น.<br/>            Read/write **str**. |
| [`is_decorative`](/slides/python-net/th/aspose.slides/sectionzoomframe/is_decorative/) | รับหรือกำหนดตัวเลือก 'Mark as decorative'<br/>            Reed/write **bool**. |
| [`shape_lock`](/slides/python-net/th/aspose.slides/sectionzoomframe/shape_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`is_grouped`](/slides/python-net/th/aspose.slides/sectionzoomframe/is_grouped/) | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่.<br/>            Read-only **bool**. |
| [`parent_group`](/slides/python-net/th/aspose.slides/sectionzoomframe/parent_group/) | คืนค่าออบเจ็กต์ GroupShape พ่อแม่หากรูปทรงถูกจัดกลุ่ม. มิฉะนั้นคืนค่า None.<br/>            Read-only [`IGroupShape`](/slides/python-net/th/aspose.slides/igroupshape). |
| [`slide`](/slides/python-net/th/aspose.slides/sectionzoomframe/slide/) | คืนค่าสไลด์แม่ของรูปทรง.<br/>            Read-only [`IBaseSlide`](/slides/python-net/th/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/th/aspose.slides/sectionzoomframe/presentation/) | คืนค่าการนำเสนอแม่ของสไลด์.<br/>            Read-only [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`graphical_object_lock`](/slides/python-net/th/aspose.slides/sectionzoomframe/graphical_object_lock/) | คืนค่าการล็อคของรูปทรง.<br/>            Read-only [`IGraphicalObjectLock`](/slides/python-net/th/aspose.slides/igraphicalobjectlock). |
| [`image_type`](/slides/python-net/th/aspose.slides/sectionzoomframe/image_type/) | รับหรือกำหนดประเภทภาพของออบเจ็กต์ซูม.<br/>            Read/write [`ZoomImageType`](/slides/python-net/th/aspose.slides/zoomimagetype).<br/>            Default value: Preview |
| [`return_to_parent`](/slides/python-net/th/aspose.slides/sectionzoomframe/return_to_parent/) | รับหรือกำหนดพฤติกรรมการนำทางในการแสดงสไลด์.<br/>            Read/write **bool**.<br/>            Default value: false |
| [`show_background`](/slides/python-net/th/aspose.slides/sectionzoomframe/show_background/) | รับหรือกำหนดค่าว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่.<br/>            Read/write **bool**.<br/>            Default value: true |
| [`zoom_image`](/slides/python-net/th/aspose.slides/sectionzoomframe/zoom_image/) | รับหรือกำหนดภาพสำหรับออบเจ็กต์ซูม.<br/>            Read/write [`IPPImage`](/slides/python-net/th/aspose.slides/ippimage). |
| [`transition_duration`](/slides/python-net/th/aspose.slides/sectionzoomframe/transition_duration/) | รับหรือกำหนดระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์.<br/>            Read/write **float**.<br/>            Default value: 1.0f |
| [`target_section`](/slides/python-net/th/aspose.slides/sectionzoomframe/target_section/) | รับหรือกำหนดออบเจ็กต์ส่วนที่ออบเจ็กต์ Section Zoom ลิงก์ไป.<br/>            Read/write [`ISection`](/slides/python-net/th/aspose.slides/isection). |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/sectionzoomframe/get_image/#) | คืนค่าภาพย่อของรูปทรง.<br/>            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [`get_image(self, bounds, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/sectionzoomframe/get_image/#shapethumbnailbounds-float-float) | คืนค่าภาพย่อของรูปทรง. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/sectionzoomframe/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [`remove_placeholder(self)`](/slides/python-net/th/aspose.slides/sectionzoomframe/remove_placeholder/#) | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [`add_placeholder(self, placeholder_to_copy_from)`](/slides/python-net/th/aspose.slides/sectionzoomframe/add_placeholder/#iplaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับออบเจ็กต์ที่ระบุ. |
| [`get_base_placeholder(self)`](/slides/python-net/th/aspose.slides/sectionzoomframe/get_base_placeholder/#) | คืนค่า placeholder shape พื้นฐาน (shape จากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดจาก).<br/>            A None is returned if the current shape is not inherited. |
| [`get_visual_bounds(self)`](/slides/python-net/th/aspose.slides/sectionzoomframe/get_visual_bounds/#) | รับขอบเขตการแสดงผลของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |

### ดูเพิ่มเติม
* class [`GraphicalObject`](/slides/python-net/th/aspose.slides/graphicalobject)
* class [`SectionZoomFrame`](/slides/python-net/th/aspose.slides/sectionzoomframe)
* class [`Shape`](/slides/python-net/th/aspose.slides/shape)
* class [`ZoomObject`](/slides/python-net/th/aspose.slides/zoomobject)
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)