---
title: ZoomFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงวัตถุ Slide Zoom ในสไลด์.
type: docs
weight: 11840
url: /th/aspose.slides/zoomframe/
---
## ZoomFrame คลาส

แสดงวัตถุ Slide Zoom ในสไลด์

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปร่างจะแสดงผลในโหมดสีดำ-ขาวอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลแบบกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการกำหนดรูปแบบการเติมสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | ส่งคืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นหน่วยจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับหรือกำหนดประเภทภาพของวัตถุ Zoom. อ่าน/เขียน [`ZoomImageType`](../zoomimagetype). ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' เป็น Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างเป็นสตริงหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนรหัสเฉพาะของสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากตำแหน่งใดก็ได้ในเอกสารได้อย่างเชื่อถือ. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนวัตถุ GroupShape พาเรนต์หากรูปร่างอยู่ในกลุ่ม. มิฉะนั้นจะคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืนตัวแทนตำแหน่งของรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวแทนตำแหน่ง. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนพาเรนต์พรีเซนเทชันของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์. อ่าน/เขียน Boolean. ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | ส่งคืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่. อ่าน/เขียน Boolean. ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนต์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | รับหรือกำหนดวัตถุสไลด์ที่วัตถุ Slide Zoom ลิงก์ถึง. อ่าน/เขียน [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเพิ่มมิติ 3d สำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับหรือกำหนดระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์. อ่าน/เขียน Single. ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนรหัสภายในที่กำหนดให้ใช้โดยแอด-อินหรือโค้ดอื่น ๆ. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรใช้เป็นคีย์ที่คงที่. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นหน่วยจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่า x ของมุมบน-ซ้ายของรูปร่างเป็นหน่วยจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่า y ของมุมบน-ซ้ายของรูปร่างเป็นหน่วยจุด. อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับหรือกำหนดภาพสำหรับวัตถุ Zoom. อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มตัวแทนตำแหน่งใหม่หากไม่มีและกำหนดคุณสมบัติตัวแทนตำแหน่งให้กับที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืนรูปร่างตัวแทนตำแหน่งพื้นฐาน (รูปร่างจากเลเอาต์และ/หรือมาสเตอร์สไลด์ที่รูปร่างปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพย่อของรูปร่าง. ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าตั้งต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพที่คำนวนจากเนื้อหาที่เรนเดอร์ของรูปร่าง |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวแทนตำแหน่ง |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* class [ZoomObject](../zoomobject)
* interface [IZoomFrame](../izoomframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->