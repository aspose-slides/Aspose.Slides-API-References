---
title: SummaryZoomSection
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงอ็อบเจ็กต์ Summary Zoom Section ในเฟรม Summary Zoom.
type: docs
weight: 10800
url: /th/aspose.slides/summaryzoomsection/
---
## คลาส SummaryZoomSection

Represents a Summary Zoom Section object in a Summary Zoom frame.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เกี่ยวข้องกับรูปร่าง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดหัวเรื่องของข้อความแทนที่ที่สัมพันธ์กับรูปร่าง อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะถูกแสดงในโหมดสีขาว-ดำอย่างไร อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | คืนค่าคำอธิบายข้อความของอ็อบเจกต์ Summary Zoom Section. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจกต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง วัดเป็นจุด อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าเครื่องมือจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | รับหรือกำหนดประเภทภาพของอ็อบเจกต์ zoom อ่าน/เขียน [`ZoomImageType`](../zoomimagetype) ค่าเริ่มต้น: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจกต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างหากจำเป็น อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32 ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจกต์ GroupShape พ่อถ้ารูปร่างอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าที่วางสำหรับรูปร่าง คืนค่า null หากรูปร่างไม่มีที่วาง อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบดิบของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | รับหรือกำหนดพฤติกรรมการนำทางในการนำเสนอ อ่าน/เขียน Boolean ค่าเริ่มต้น: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | รับหรือกำหนดค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่ อ่าน/เขียน Boolean ค่าเริ่มต้น: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์แม่ของรูปร่าง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | รับหรือกำหนดอ็อบเจกต์ส่วนที่อ็อบเจกต์ Section Zoom เชื่อมโยงไป อ่าน/เขียน [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเส้น 3 มิติสำหรับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | คืนค่าชื่อเรื่องข้อความของอ็อบเจกต์ Summary Zoom Section. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | รับหรือกำหนดระยะเวลาเปลี่ยนระหว่าง Zoom และสไลด์ อ่าน/เขียน Single ค่าเริ่มต้น: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในที่มีขอบเขตการนำเสนอซึ่งตั้งใจให้ใช้โดยแอดอินหรือโค้ดอื่น เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ดังนั้นจึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว UInt32 ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง วัดเป็นจุด อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง วัดเป็นจุด อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง วัดเป็นจุด อ่าน/เขียน Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | รับหรือกำหนดภาพสำหรับอ็อบเจกต์ zoom อ่าน/เขียน [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปร่างที่ด้านหน้า อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มที่วางใหม่หากไม่มีและตั้งค่าคุณลักษณะของที่วางให้กับอ็อบเจกต์ที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูปร่างที่วางพื้นฐาน (รูปร่างจากเค้าโครงและ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมาจาก) หากรูปร่างปัจจุบันไม่ได้สืบทอดจะคืนค่า null |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนรูปย่อของรูปร่าง ใช้ประเภท ShapeThumbnailBounds.Shape เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนรูปย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ที่วาง |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [SectionZoomFrame](../sectionzoomframe)
* อินเทอร์เฟซ [ISummaryZoomSection](../isummaryzoomsection)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->