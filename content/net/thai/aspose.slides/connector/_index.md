---
title: Connector
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: เป็นตัวเชื่อมต่อ.
type: docs
weight: 2690
url: /th/aspose.slides/connector/
---
## Connector คลาส

เป็นตัวเชื่อมต่อ

```csharp
public class Connector : GeometryShape, IConnector
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของรูป. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูป. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูป. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปจะเรนเดอร์ในโหมดแสดงผลสีดำ-ขาวอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูป. อ่านอย่างเดียว Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | ส่งคืนล็อคของเชื่อมต่อ. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูป. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูป. หมายเหตุ: สามารถคืนค่า null สำหรับรูปบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | ส่งคืนหรือกำหนดรูปที่เชื่อมต่อปลายของตัวเชื่อมต่อ. อ่าน/เขียน [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปที่ปลาย. อ่าน/เขียน UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูป. หมายเหตุ: สามารถคืนค่า null สำหรับรูปบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติกรอบรูป. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ส่งคืนหรือกำหนดความสูงของรูป, หน่วยเป็น point. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปซ่อนอยู่หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับเมาส์โฮเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | ส่งคืนหรือกำหนดตัวเลือก 'Mark as decorative'. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปเส้นสำหรับรูป. หมายเหตุ: สามารถคืนค่า null สำหรับรูปบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูป. ต้องไม่เป็นค่า null. ใช้ค่า string ว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุรูปและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปจากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจ็กต์ GroupShape พาเรนท์ถ้ารูปถูกจัดกลุ่ม. หากไม่ใช่จะคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder สำหรับรูป. คืนค่า null หากรูปไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนพาเรนท์ presentation ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติกรอบรูปดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | ส่งคืนล็อคของรูป. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนอ็อบเจ็กต์สไตล์ของรูป. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape. อ่าน/เขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนท์ของรูป. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | ส่งคืนหรือกำหนดรูปที่เชื่อมต่อจุดเริ่มต้นของตัวเชื่อมต่อ. อ่าน/เขียน [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปเริ่มต้น. อ่าน/เขียน UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูป. หมายเหตุ: สามารถคืนค่า null สำหรับรูปบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในที่กำหนดขอบเขตการนำเสนอเพื่อใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำอย่างถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | ส่งคืนหรือกำหนดความกว้างของรูป, หน่วยเป็น point. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | ส่งคืนหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูป, หน่วยเป็น point. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | ส่งคืนหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูป, หน่วยเป็น point. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปในลำดับ z. Shapes[0] คืนรูปที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งคืนอาเรย์ของส่วนประกอบของรูป. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืนรูป placeholder พื้นฐาน (รูปจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปปัจจุบันสืบทอดมาจาก). จะคืนค่า null หากรูปปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต. พิกัดอิงตามมุมซ้ายบนของรูป. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนรูปย่อของรูป. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนรูปย่อของรูป. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | ส่งคืนขอบเขตภาพของรูปที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปนี้ไม่ใช่ placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | ปรับเส้นเชื่อมต่อใหม่เพื่อให้เส้นทางสั้นที่สุดระหว่างรูปที่เชื่อมต่อ. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตรูปทรงของรูปจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องอิงตามมุมซ้ายบนของรูป. เปลี่ยนประเภทของรูป ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตรูปทรงของรูปจากอาเรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องอิงตามมุมซ้ายบนของรูป. เปลี่ยนประเภทของรูป ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IConnector](../iconnector)
* เนมส페ซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->