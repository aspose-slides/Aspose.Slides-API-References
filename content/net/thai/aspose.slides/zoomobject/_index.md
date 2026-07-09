---
title: ZoomObject
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นอ็อบเจ็กต์ Zoom ในสไลด์
type: docs
weight: 11870
url: /th/aspose.slides/zoomobject/
---
## ZoomObject คลาส

Represents an Zoom object in a slide.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า或กำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า或กำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปทรงจะถูกแสดงอย่างไรในโหมดสีดำขาว. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติกำหนดรูปแบบการเติมสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนหรือกำหนดคุณสมบัติของเฟรมรูปทรง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนหรือกำหนดลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนผู้จัดการลิงก์ไฮเปอร์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนหรือกำหนดลิงก์ไฮเปอร์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับหรือกำหนดประเภทรูปภาพของวัตถุ Zoom. อ่าน/เขียน [`ZoomImageType`](../zoomimagetype). ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติกำหนดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนหรือกำหนดชื่อของรูปทรง. ต้องไม่เป็นค่าว่าง. ใช้ค่าสตริงว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าเอกลักษณ์เฉพาะของสไลด์ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้จากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนอ็อบเจ็กต์ GroupShape พ่อแม่ถ้ารูปทรงอยู่ในกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืน placeholder ของรูปทรง. คืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนพรีเซนเทชันแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนหรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน Boolean. ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน/เขียน Boolean. ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์แม่ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟ็กต์ 3D สำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับหรือกำหนดระยะเวลาการเปลี่ยนจาก Zoom ไปสไลด์. อ่าน/เขียน Single. ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าอิลิเดนไทเซอร์ภายในที่กำหนดตามพรีเซนเทชันเพื่อใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม, ไม่ควรถือว่าเป็นกุญแจเฉพาะที่คงที่. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปทรงเป็นจุด. อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับหรือกำหนดรูปภาพสำหรับวัตถุ Zoom. อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## วิธีการ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นตามที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูป placeholder พื้นฐาน (รูปจากเลเอาต์และ/หรือมาสเตอร์สไลด์ที่รูปปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพย่อของรูปทรง. ประเภท ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ได้เป็น placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปเป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปเป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* class [GraphicalObject](../graphicalobject)
* interface [IZoomObject](../izoomobject)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->