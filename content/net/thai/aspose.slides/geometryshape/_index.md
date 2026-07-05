---
title: GeometryShape
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงถึงคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
type: docs
weight: 4970
url: /th/aspose.slides/geometryshape/
---
## GeometryShape คลาส

แสดงถึงคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | คืนค่าคอลเลกชันของค่าการปรับของรูปร่าง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะถูกแสดงในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นหน่วยพ้อยต์. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่าหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape ต้นแม่หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตำแหน่งตัวแทนสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติของเฟรมรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนตามทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | คืนค่าอ็อบเจ็กต์สไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | คืนค่าหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าตั้งต้น. อ่าน/เขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในที่กำหนดตามการนำเสนอและมุ่งหมายให้ใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, ไม่ควรถือเป็นคีย์ที่ไม่ซ้ำถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นหน่วยพ้อยต์. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่างเป็นหน่วยพ้อยต์. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่างเป็นหน่วยพ้อยต์. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้า. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ให้กับที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและคืนค่าอาเรย์ขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder รูปร่างพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | คืนค่าการคัดลอกของเส้นทางของรูปทรงเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](./shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](./shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [Shape](../shape)
* อินเทอร์เฟส [IGeometryShape](../igeometryshape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->