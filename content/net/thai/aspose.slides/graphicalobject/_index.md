---
title: GraphicalObject
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงวัตถุกราฟิกเชิงนามธรรม.
type: docs
weight: 5090
url: /th/aspose.slides/graphicalobject/
---
## GraphicalObject คลาส

แสดงถึงวัตถุกราฟิกเชิงนามธรรม.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือ ตั้งค่าข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อของข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติระบุว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว.. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของกรอบรูปทรง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | คืนค่า หรือ ตั้งค่าความสูงของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดไว้สำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการลิงก์ไฮเปอร์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดไว้สำหรับการเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | คืนค่า หรือ ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อของรูปทรง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า identifier ที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้จากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปทรงถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตัวตำแหน่งสำหรับรูปทรง. คืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของกรอบรูปทรงดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ ตั้งค่ามาตรฐานขององศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์แม่ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่า identifier ภายในระดับการนำเสนอที่ออกแบบมาสำหรับใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์เอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | คืนค่า หรือ ตั้งค่าความกว้างของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | คืนค่า หรือ ตั้งค่าพิกัด x ของมุมบนซ้ายของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | คืนค่า หรือ ตั้งค่าพิกัด y ของมุมบนซ้ายของรูปทรง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนค่ารูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนค่ารูปทรงที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมา). คืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปทรง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | คืนค่าขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [Shape](../shape)
* อินเทอร์เฟส [IGraphicalObject](../igraphicalobject)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->