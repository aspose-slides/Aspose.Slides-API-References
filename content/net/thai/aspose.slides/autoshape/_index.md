---
title: AutoShape
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึง AutoShape.
type: docs
weight: 900
url: /th/aspose.slides/autoshape/
---
## AutoShape คลาส

แสดงถึง AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | คืนค่าชุดของค่าการปรับของรูปร่าง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | คืนค่าการล็อคของ autoshape. อ่านอย่างเดียว [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปจะเรนเดอร์อย่างไรในโหมดการแสดงผลขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ซึ่งมีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นพอยต์. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าเป็นสตริงว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุที่เป็นเอกลักษณ์ระดับสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตัวจัดตำแหน่งของรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวจัดตำแหน่ง. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าพรีเซนเทชั่นพ่อแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | คืนค่าการล็อคของรูปร่าง. อ่านอย่างเดียว [`IAutoShapeLock`](../iautoshapelock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | คืนค่าอ็อบเจ็กต์สไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | คืนค่าหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน/เขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์พ่อแม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | คืนค่าอ็อบเจ็กต์ TextFrame สำหรับ AutoShape. อ่านอย่างเดียว [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในระดับพรีเซนเทชั่นที่ตั้งใจให้ใช้โดยส่วนเสริมหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | กำหนดว่ารูปร่างอัตโนมัตินี้ควรถูกเติมด้วยพื้นหลังของสไลด์แทนที่กำหนดโดยสไตล์หรือรูปแบบการเติม. อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นพอยต์. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นพอยต์. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นพอยต์. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มตัวจัดตำแหน่งใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวจัดตำแหน่งให้เป็นค่าที่ระบุ. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | เพิ่ม TextFrame ใหม่ให้กับรูปร่าง. หากรูปร่างมี TextFrame อยู่แล้ว จะเปลี่ยนข้อความเท่านั้น. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่ารูปร่างตัวจัดตำแหน่งพื้นฐาน (รูปร่างจากเค้าโครงและ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมาจาก). คืนค่า null ถ้ารูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | คืนค่าการคัดลอกของเส้นทางของรูปร่างเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่เป็นตัวจัดตำแหน่ง. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IAutoShape](../iautoshape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->