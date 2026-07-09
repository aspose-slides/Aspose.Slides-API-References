---
title: Connector
second_title: Aspose.Sildes สำหรับ .NET - เอกสารอ้างอิง API
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งกลับคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งกลับหรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape. อ่านและเขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งกลับหรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับ shape. อ่านและเขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปทรงจะถูกแสดงผลอย่างไรในโหมดสีขาว-ดำ. อ่านและเขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งกลับจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | ส่งกลับการล็อกของ connector. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งกลับข้อมูลที่กำหนดเองของ shape. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งกลับวัตถุ EffectFormat ซึ่งประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจส่งกลับ null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | ส่งกลับหรือกำหนด shape ที่จะต่อท้ายของ connector. อ่านและเขียน [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | ส่งกลับหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape สุดท้าย. อ่านและเขียน UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งกลับวัตถุ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape. หมายเหตุ: อาจส่งกลับ null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งกลับหรือกำหนดคุณสมบัติของกรอบ shape. อ่านและเขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของ shape หน่วยเป็นจุด. อ่านและเขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่า shape จะถูกซ่อนหรือไม่. อ่านและเขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งกลับหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเม้าส์. อ่านและเขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งกลับผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งกลับหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเม้าส์อยู่เหนือ. อ่านและเขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative'. อ่านและเขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งกลับวัตถุ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: อาจส่งกลับ null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งกลับหรือกำหนดชื่อของ shape. ต้องไม่เป็นค่า null. ใช้สตริงว่างหากต้องการ. อ่านและเขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งกลับตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งกลับออบเจ็กต์ GroupShape พาเรนท์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นส่งกลับ null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งกลับ placeholder ของ shape. ส่งกลับ null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งกลับพรีเซ็นเทชันพาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งกลับหรือกำหนดคุณสมบัติกรอบ shape ดิบ. อ่านและเขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งกลับหรือกำหนดจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่านและเขียน Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | ส่งกลับการล็อกของ shape. อ่านอย่างเดียว [`IConnectorLock`](../iconnectorlock). (2 คุณสมบัติ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งกลับออบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | ส่งกลับหรือกำหนดประเภท AutoShape. อ่านและเขียน [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งกลับสไลด์พาเรนท์ของ shape. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | ส่งกลับหรือกำหนด shape ที่จะต่อจุดเริ่มต้นของ connector. อ่านและเขียน [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | ส่งกลับหรือกำหนดดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. อ่านและเขียน UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งกลับวัตถุ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับ shape. หมายเหตุ: อาจส่งกลับ null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งกลับตัวระบุภายในที่ใช้สำหรับการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของ shape หน่วยเป็นจุด. อ่านและเขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นจุด. อ่านและเขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นจุด. อ่านและเขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งกลับตำแหน่งของ shape ใน z-order. Shapes[0] ส่งกลับ shape ที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] ส่งกลับ shape ที่อยู่ด้านหน้าของ z-order. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ตามที่ระบุ. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งกลับอาร์เรย์ขององค์ประกอบของ shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งกลับ shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมา). จะคืนค่า null หาก shape ปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งกลับสำเนาเส้นทางของ shape เรขาคณิต. พิกัดอ้างอิงจากมุมซ้ายบนของ shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งกลับภาพย่อของ shape. ประเภท ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งกลับภาพย่อของ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตการแสดงผลของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่า shape นี้ไม่ได้เป็น placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | เปลี่ยนเส้นทางของ connector ให้ใช้เส้นทางที่สั้นที่สุดระหว่าง shape ที่เชื่อมต่อ. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของ shape จากออบเจ็กต์ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของ shape จากอาร์เรย์ของ [`IGeometryPath`](../igeometrypath). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([`ShapeType`](../geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape)
* อินเทอร์เฟซ [IConnector](../iconnector)
* เนมส페ซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->