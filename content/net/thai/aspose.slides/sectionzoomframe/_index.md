---
title: SectionZoomFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนวัตถุ Section Zoom ในสไลด์
type: docs
weight: 9780
url: /th/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame คลาส

เป็นการแทนวัตถุ Section Zoom ในสไลด์หนึ่ง.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือ ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติเช่นระบุว่ารูปร่างจะแสดงผลในโหมดสีดำ-ขาวอย่างไร.. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของรูปร่าง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่ประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติการเติม อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของเฟรมรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง หน่วยเป็น points อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการลิงก์ไฮเปอร์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการวางเมาส์เหนือ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับหรือกำหนดประเภทภาพของอ็อบเจ็กต์ zoom อ่าน/เขียน [`ZoomImageType`](../zoomimagetype). ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อของรูปร่าง ต้องไม่เป็นค่า null หากต้องการให้เป็นสตริงว่างใช้ค่า "" อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสารอย่างเชื่อถือได้ อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปร่างเป็นกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตัวแสดงตำแหน่งสำหรับรูปร่าง หากรูปร่างไม่มีตัวแสดงตำแหน่งจะคืนค่า null อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเรนท์ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์ อ่าน/เขียน Boolean. ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ ตั้งค่าค่ามุมองศาที่รูปร่างระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ อ่าน/เขียน Boolean. ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเรนท์ของรูปร่าง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | รับหรือกำหนดอ็อบเจ็กต์ section ที่อ็อบเจ็กต์ Section Zoom เชื่อมโยงไปอ่าน/เขียน [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับหรือกำหนดระยะเวลาในการเปลี่ยนจาก Zoom ไปยังสไลด์ อ่าน/เขียน Single. ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในที่ใช้ในระดับการนำเสนอซึ่งออกแบบมาสำหรับใช้โดยแอดอินหรือโค้ดอื่นๆ เนื่องจากค่าดังกล่าวอาจถูกกำหนดค่าใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง หน่วยเป็น points อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่าง หน่วยเป็น points อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่าง หน่วยเป็น points อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับหรือกำหนดภาพสำหรับอ็อบเจ็กต์ zoom อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z-order Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z-order และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z-order อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder รูปร่างพื้นฐาน (รูปร่างจากเค้าโครงและ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมา) หากรูปร่างปัจจุบันไม่ได้สืบทอดจะคืนค่า null |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพขนาดย่อของรูปร่าง ใช้ชนิด ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขตภาพขนาดย่อ |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพขนาดย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหของรูปร่างเป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [ZoomObject](../zoomobject)
* อินเทอร์เฟซ [ISectionZoomFrame](../isectionzoomframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->