---
title: SmartArtShape
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงถึงรูปร่าง SmartArt
type: docs
weight: 10680
url: /th/aspose.slides.smartart/smartartshape/
---
## SmartArtShape คลาส

แสดงถึงรูปร่าง SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | ส่งกลับคอลเลกชันของค่าการปรับของรูปร่าง. อ่านอย่างเดียว [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งกลับหรือกำหนดข้อความทดแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งกลับหรือกำหนดชื่อของข้อความทดแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติจัดกำหนดว่ารูปร่างจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งกลับจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งกลับข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งกลับวัตถุ EffectFormat ซึ่งบรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งกลับวัตถุ FillFormat ซึ่งบรรจุคุณสมบัติการเติมของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งกลับหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นพ้อยท์. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งกลับผู้จัดการ hyperlink. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการเอาเมาส์ไปวางเหนือ. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งกลับวัตถุ LineFormat ซึ่งบรรจุคุณสมบัติการจัดรูปแบบเส้นของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งกลับหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ให้ใช้สตริงว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งกลับตัวระบุที่เป็นเอกลักษณ์แบบสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งกลับวัตถุ GroupShape ของพาเรนต์หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งกลับ placeholder ของรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งกลับการนำเสนอของพาเรนต์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งกลับหรือกำหนดคุณสมบัติของเฟรมรูปร่างแบบดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งกลับหรือกำหนดจำนวนองศาที่รูปร่างถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | ส่งกลับล็อกของรูปร่าง. อ่านอย่างเดียว [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | ส่งกลับอ็อบเจ็กต์สไตล์ของรูปร่าง. อ่านอย่างเดียว [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | ส่งกลับหรือกำหนดประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน/เขียน [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งกลับสไลด์พาเรนต์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | ส่งกลับข้อความของรูปร่าง SmartArt. อ่านอย่างเดียว [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งกลับวัตถุ ThreeDFormat ซึ่งบรรจุคุณสมบัติเอฟเฟกต์ 3D ของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งกลับตัวระบุภายในที่มีขอบเขตการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่คงที่และเป็นเอกลักษณ์. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นพ้อยท์. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่าง, วัดเป็นพ้อยท์. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่าง, วัดเป็นพ้อยท์. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งกลับตำแหน่งของรูปร่างใน z-order. Shapes[0] คืนรูปร่างที่ด้านหลังสุดของ z-order, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่ด้านหน้ายสุดของ z-order. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและส่งกลับอาร์เรย์ขององค์ประกอบของรูปร่าง |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งกลับรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ส่งกลับสำเนาของเส้นทางของรูปร่างเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งกลับรูปย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งกลับรูปย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดตเรขาคณิตของรูปร่างจากวัตถุ [`IGeometryPath`](../../aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) เป็น Custom |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../../aspose.slides/igeometrypath). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง. เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) เป็น Custom |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../../aspose.slides/geometryshape)
* อินเทอร์เฟซ [ISmartArtShape](../ismartartshape)
* เนมสเปซ [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->