---
title: SummaryZoomSection
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวแทนของออบเจกต์ Summary Zoom Section ในกรอบ Summary Zoom.
type: docs
weight: 10780
url: /th/aspose.slides/summaryzoomsection/
---
## คลาส SummaryZoomSection

เป็นตัวแทนของวัตถุ Summary Zoom Section ในกรอบ Summary Zoom.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดหัวเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ระบุว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | คืนค่าคำอธิบายข้อความของวัตถุ Summary Zoom Section. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการฟอร์แมตการเติมสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัตินี้ อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของกรอบรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง วัดเป็นพอยท์ อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับหรือกำหนดประเภทภาพของวัตถุซูม อ่าน/เขียน [`ZoomImageType`](../zoomimagetype). ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติดีไซน์เส้นสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างถ้าจำเป็น อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ของรูปร่างซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างน่าเชื่อถือจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปร่างอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของรูปร่าง คืนค่า null หากรูปร่างไม่มี placeholder อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเรนท์ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของกรอบรูปร่างดิบ อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับหรือกำหนดพฤติกรรมการนำทางในสไลด์โชว์ อ่าน/เขียน Boolean. ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับหรือกำหนดค่าที่ระบุว่าซูมจะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน/เขียน Boolean. ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสตไลด์พาเรนท์ของรูปร่าง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | รับหรือกำหนดออบเจ็กต์ส่วนที่วัตถุ Section Zoom เชื่อมโยงถึง อ่าน/เขียน [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | คืนค่าชื่อข้อความของวัตถุ Summary Zoom Section. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับหรือกำหนดระยะเวลาการเปลี่ยนระหว่างซูมและสไลด์ อ่าน/เขียน Single. ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในระดับการนำเสนอที่ออกแบบมาสำหรับการใช้โดยแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ดังนั้นไม่ควรถือเป็นคีย์ที่ไม่ซ้ำแบบถาวร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง วัดเป็นพอยท์ อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง วัดเป็นพอยท์ อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง วัดเป็นพอยท์ อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับหรือกำหนดภาพสำหรับวัตถุซูม อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z-order Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z-order และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z-order อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ตามที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder รูปแบบพื้นฐาน (รูปจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก) หากรูปร่างปัจจุบันไม่ได้สืบทอด จะคืนค่า null |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปร่าง ShapeThumbnailBounds.Shape เป็นประเภทขอบเขตภาพย่อที่ใช้โดยค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวนจากเนื้อหาที่ถูกเรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [SectionZoomFrame](../sectionzoomframe)
* อินเทอร์เฟซ [ISummaryZoomSection](../isummaryzoomsection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->