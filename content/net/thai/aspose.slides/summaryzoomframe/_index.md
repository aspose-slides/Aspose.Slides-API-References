---
title: SummaryZoomFrame
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงวัตถุ Summary Zoom ในสไลด์หนึ่ง.
type: docs
weight: 10770
url: /th/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame คลาส

แสดงวัตถุ Summary Zoom ในสไลด์หนึ่ง.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือ กำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือ กำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะแสดงผลอย่างไรในโหมดแสดงผลสีดำ-ขาว.. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจกต์ EffectFormat ที่ประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจกต์ FillFormat ที่ประกอบด้วยคุณสมบัติการเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับ หรือ กำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ กำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับเมาส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับ หรือ กำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | รับเค้าโครงของส่วน Summary Zoom ในกรอบ. ค่าดีฟอลต์คือ GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจกต์ LineFormat ที่ประกอบด้วยคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ กำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างถ้าจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าอีดินตี้ที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างน่าเชื่อถือจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจกต์ GroupShape พาเรนท์หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าตัวแสดงตำแหน่งสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวแสดงตำแหน่ง. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ กำหนดคุณสมบัติกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ กำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าหน้าพาเรนท์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | รับ [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) สำหรับอ็อบเจกต์ Summary Zoom Frame. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับประเภทรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าอีดินตี้ภายในระดับการนำเสนอซึ่งออกแบบสำหรับใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, ไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับ หรือ กำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับ หรือ กำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับ หรือ กำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้า. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มตัวแสดงตำแหน่งใหม่หากไม่มีและกำหนดคุณสมบัติตัวแสดงตำแหน่งเป็นค่าที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่ารูปร่างตัวแสดงตำแหน่งพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าตัวย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าตัวย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวแสดงตำแหน่ง. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [ISummaryZoomFrame](../isummaryzoomframe)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->