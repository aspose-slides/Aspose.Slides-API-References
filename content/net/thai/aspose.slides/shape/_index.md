---
title: Shape
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: เป็นตัวแทนของรูปทรงบนสไลด์
type: docs
weight: 9850
url: /th/aspose.slides/shape/
---
## คลาส Shape

เป็นตัวแทนของรูปทรงบนสไลด์หนึ่ง.

```csharp
public class Shape : IShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปทรงจะถูกแสดงในโหมดสีดำ-ขาวอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนของจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่ประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงประเภทบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่ประกอบด้วยคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงประเภทบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปทรง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับ หรือกำหนดความสูงของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าไฮเปอร์ลิงก์เมเนเจอร์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับ หรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่ประกอบด้วยคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงประเภทบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปทรง. ต้องไม่เป็น null. ใช้ค่าว่างถ้าจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าอีดินติเพียงเอกเทศระดับสไลด์ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์ หากรูปทรงเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของรูปทรง. คืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่า presentation พาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบดิบของรูปทรง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | คืนค่าการล็อกของรูปทรง. อ่านอย่างเดียว [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเรนท์ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงประเภทบางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในระดับ presentation ที่ออกแบบให้ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ยูนีคที่คงที่. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับ หรือกำหนดความกว้างของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับ หรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับ หรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่ถ้ายังไม่มีและกำหนดคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่ารูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาท์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมาจาก). จะคืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | คืนค่า thumbnail ของรูปทรง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้นสำหรับขอบเขต thumbnail ของรูปทรง. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | คืนค่า thumbnail ของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IShape](../ishape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->