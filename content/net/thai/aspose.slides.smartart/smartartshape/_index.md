---
title: SmartArtShape
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: เป็นตัวแทนของรูปร่าง SmartArt
type: docs
weight: 10660
url: /th/aspose.slides.smartart/smartartshape/
---
## SmartArtShape คลาส

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | คืนค่าชุดค่าปรับของรูปร่าง อ่านอย่างเดียว [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของรูปร่าง อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่า EffectFormat object ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่า FillFormat object ที่มีคุณสมบัติการเติมรูปแบบสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติการเติม อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติเฟรมของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | คืนค่าหรือกำหนดความสูงของรูปร่าง หน่วยเป็นพอยต์ อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนไว้หรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่า hyperlink manager อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่าหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือรูปร่าง อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นส่วนหนึ่งของกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่า LineFormat object ที่มีคุณสมบัติการกำหนดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างหากต้องการ อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า identifier ที่ไม่ซ้ำกันในระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปร่างเป็นกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของรูปร่าง คืนค่า null ถ้ารูปร่างไม่มี placeholder อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเรนท์ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติเฟรมดิบของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | คืนค่าล็อกของรูปร่าง อ่านอย่างเดียว [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | คืนค่าอ็อบเจ็กต์สไตล์ของรูปร่าง อ่านอย่างเดียว [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | คืนค่าหรือกำหนดประเภท geometry preset หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน/เขียน [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเรนท์ของรูปร่าง อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | คืนค่าเนื้อความของรูปร่าง SmartArt อ่านอย่างเดียว [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่า ThreeDFormat object ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3d อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่า identifier ภายในระดับการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-ins หรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกเปลี่ยนโดยผู้ใช้หรือโดยโปรแกรมจึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง หน่วยเป็นพอยต์ อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์ อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์ อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างใน z-order Shapes[0] ให้รูปร่างที่อยู่ด้านหลังสุดของ z-order และ Shapes[Shapes.Count - 1] ให้รูปร่างที่อยู่ด้านหน้าสุดของ z-order อ่านอย่างเดียว Int32. |

## วิธีการ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นที่กำหนด. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของรูปร่าง. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder รูปร่างพื้นฐาน (รูปร่างจากเลเอาต์หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอด) คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | คืนค่าทางเดินของรูปร่าง geometry พิกัดอ้างอิงจากมุมซ้ายบนของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่า thumbnail ของรูปร่าง ShapeThumbnailBounds.Shape เป็นประเภท bounds เริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่า thumbnail ของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับ bounds เชิงภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | อัปเดต geometry ของรูปร่างจากอ็อบเจ็กต์ [`IGeometryPath`](../../aspose.slides/igeometrypath) พิกัดต้องอ้างอิงจากมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) เป็น Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | อัปเดต geometry ของรูปร่างจากอาร์เรย์ของ [`IGeometryPath`](../../aspose.slides/igeometrypath) พิกัดต้องอ้างอิงจากมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) เป็น Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GeometryShape](../../aspose.slides/geometryshape)
* อินเทอร์เฟซ [ISmartArtShape](../ismartartshape)
* เนมสเปซ [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->