---
title: ZoomObject
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงวัตถุ Zoom ในสไลด์หนึ่ง.
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

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติเพิ่มเติมระบุว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร.. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่าน-อย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของรูปร่าง. อ่าน-อย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่า EffectFormat object ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่าน-อย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่า FillFormat object ที่มีคุณสมบัติการเติมสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่าน-อย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่าน-อย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับ หรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเม้าส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่าน-อย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเม้าส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับ หรือกำหนดประเภทภาพของวัตถุ Zoom. อ่าน/เขียน [`ZoomImageType`](../zoomimagetype). ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับ หรือกำหนดตัวเลือก 'ทำเครื่องหมายเป็นของตกแต่ง' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่. อ่าน-อย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่าน-อย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่า LineFormat object ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่าน-อย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างถ้าจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าอักษรระบุที่มีความเฉพาะระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่าน-อย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจกต์ GroupShape พ่อแม่หากรูปร่างถูกจัดกลุ่ม. หากไม่เช่นนั้นคืนค่า null. อ่าน-อย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตัวเก็บตำแหน่งสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวเก็บตำแหน่ง. อ่าน-อย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพ่อแม่ของสไลด์. อ่าน-อย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับ หรือกำหนดพฤติกรรมการนำทางในการแสดงสไลด์. อ่าน/เขียน Boolean. ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่กำหนดถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่าน-อย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับ หรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน/เขียน Boolean. ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พ่อแม่ของรูปร่าง. อ่าน-อย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่า ThreeDFormat object ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่าน-อย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับ หรือกำหนดระยะเวลาในการเปลี่ยนระหว่าง Zoom กับสไลด์. อ่าน/เขียน Single. ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าอัตภายในที่เป็นเอกลักษณ์ระดับการนำเสนอซึ่งออกแบบมาสำหรับใช้งานโดยแอดอินหรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่คงที่และไม่ซ้ำกัน. อ่าน-อย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับ หรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับ หรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับ หรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับ หรือกำหนดรูปภาพสำหรับวัตถุ Zoom. อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่าน-อย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้กับที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก). จะคืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่า thumbnail ของรูปร่าง. ใช้รูปแบบ ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้นสำหรับขอบเขต thumbnail. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่า thumbnail ของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [IZoomObject](../izoomobject)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->