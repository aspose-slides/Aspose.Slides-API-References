---
title: AutoShape
second_title: Aspose.Sildes สำหรับอ้างอิง API ของ .NET
description: เป็นตัวแทนของ AutoShape.
type: docs
weight: 900
url: /th/aspose.slides/autoshape/
---
## AutoShape คลาส

Represents an AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของรูปร่าง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | ส่งคืนการล็อคของ autoshape. อ่านอย่างเดียว [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะแสดงผลอย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนวัตถุ EffectFormat ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนวัตถุ FillFormat ที่มีคุณสมบัติการเติมรูปแบบสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นส่วนของกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ใช้ค่าว่างถ้าจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุเฉพาะที่มีขอบเขตตามสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากตำแหน่งใดในเอกสารได้อย่างเชื่อถือได้. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนวัตถุ GroupShape พ่อแม่หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืนตัวเติมของรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวเติม. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของเฟรมรูปร่างที่ไม่ผ่านการประมวลผล. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | ส่งคืนการล็อคของรูปร่าง. อ่านอย่างเดียว [`IAutoShapeLock`](../iautoshapelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนวัตถุสไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยน ทุกค่าการปรับจะรีเซ็ตเป็นค่าตั้งต้น. อ่าน/เขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | ส่งคืนวัตถุ TextFrame สำหรับ AutoShape. อ่านอย่างเดียว [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเสียงสามมิติสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติสามมิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในที่มีขอบเขตตามการนำเสนอซึ่งออกแบบมาเพื่อใช้โดยแอดออนหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | กำหนดว่ารูปร่างอัตโนมัตินี้ควรถูกเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติม. อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่าพิกัด x ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่าพิกัด y ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้า. อ่านอย่างเดียว Int32. |

## เมธอด

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มตัวเติมใหม่หากไม่มีและกำหนดคุณสมบัติตัวเติมเป็นค่าที่ระบุ. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | เพิ่ม TextFrame ใหม่ให้กับรูปร่าง. หากรูปร่างมี TextFrame อยู่แล้วจึงเปลี่ยนข้อความเท่านั้น. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืนรูปร่างตัวเติมพื้นฐาน (รูปร่างจากเลย์เอาต์หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอด). คืนค่า null หากรูปร่างปัจจุบันไม่สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต. พิกัดอิงตามมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตเชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวเติม. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องอิงตามมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาเรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องอิงตามมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IAutoShape](../iautoshape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->