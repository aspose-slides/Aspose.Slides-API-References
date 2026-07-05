---
title: Connector
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงตัวเชื่อมต่อ.
type: docs
weight: 2670
url: /th/aspose.slides/connector/
---
## คลาส Connector

แสดงถึงตัวเชื่อมต่อ.

```csharp
public class Connector : GeometryShape, IConnector
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งคืนคอลเลกชันของค่าการปรับของรูปทรง. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติระบุว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | ส่งคืนการล็อกของตัวเชื่อมต่อ. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจ็กต์ EffectFormat ซึ่งประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | ส่งคืนหรือกำหนดรูปทรงที่ต่อท้ายของตัวเชื่อมต่อจะเชื่อมต่อ. อ่าน/เขียน [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปทรงท้าย. อ่าน/เขียน UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจ็กต์ FillFormat ที่ประกอบด้วยคุณสมบัติการเติมสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบรูปทรง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงซ่อนอยู่หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'ทำเครื่องหมายว่าเป็นของประดับ' . อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจ็กต์ LineFormat ที่ประกอบด้วยคุณสมบัติการวาดเส้นสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการวาดเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปทรง. ต้องไม่เป็นค่า null. หากต้องการใช้ค่าเปล่าให้ใส่สตริงว่าง. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนรหัสประจำตัวที่มีความหมายเฉพาะต่อสไลด์และคงที่ตลอดอายุของรูปทรง, ทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างมั่นใจจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปทรงเป็นกลุ่ม. มิฉะนั้นจะคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของรูปทรง. จะคืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบรูปแบบดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปทรงกำหนดหมุนรอบแกน Z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | ส่งคืนการล็อกของรูปทรง. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งคืนอ็อบเจ็กต์สไตล์ของรูปทรง. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | ส่งคืนหรือกำหนดประเภท AutoShape. อ่าน/เขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์แม่ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | ส่งคืนหรือกำหนดรูปทรงที่ต่อจุดเริ่มต้นของตัวเชื่อมต่อ. อ่าน/เขียน [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | ส่งคืนหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับรูปทรงเริ่มต้น. อ่าน/เขียน UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนรหัสภายในที่มีขอบเขตการนำเสนอซึ่งออกแบบมาสำหรับใช้โดยแอด-อินหรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือเป็นคีย์ที่คงที่เฉพาะ. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด X ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด Y ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปทรงในลำดับ Z. Shapes[0] ส่งคืนรูปทรงที่อยู่ด้านหลังสุดของลำดับ Z, และ Shapes[Shapes.Count - 1] ส่งคืนรูปทรงที่อยู่ด้านหน้าสุดของลำดับ Z. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งกลับอาร์เรย์ของอิลิเมนต์ของรูปทรง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืนรูป placeholder พื้นฐาน (รูปจากเลย์เอาต์และ/หรือมาสเตอร์สไลด์ที่รูปปัจจุบันสืบทอดมา). จะคืนค่า null หากรูปปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งคืนสำเนาของเส้นทางของรูปทรงเรขาคณิต. พิกัดเป็นค่าตามมุมซ้ายบนของรูปทรง. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพย่อของรูปทรง. ชนิด ShapeThumbnailBounds.Shape จะถูกใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพย่อของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | กำหนดเส้นทางใหม่ของตัวเชื่อมต่อให้ใช้เส้นทางที่สั้นที่สุดระหว่างรูปทรงที่เชื่อมต่อ. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปทรงจากอ็อบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องเป็นค่าตามมุมซ้ายบนของรูปทรง. เปลี่ยนประเภทของรูปทรง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปทรงจากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องเป็นค่าตามมุมซ้ายบนของรูปทรง. เปลี่ยนประเภทของรูปทรง ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IConnector](../iconnector)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->