---
title: Ink
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงออบเจ็กต์หมึกบนสไลด์.
type: docs
weight: 7570
url: /th/aspose.slides.ink/ink/
---
## Ink คลาส

แสดงถึงออบเจ็กต์หมึกบนสไลด์.

```csharp
public class Ink : GraphicalObject, IInk
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือ ตั้งค่าข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือ ตั้งค่าชื่อเรื่องของข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ซึ่งบรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ซึ่งบรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของกรอบรูปทรง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อคของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปทรงหน่วยเป็นพอยต์. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือ ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าตัวจัดการ hyperlink. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือ ตั้งค่า hyperlink ที่กำหนดสำหรับการเมาส์อยู่เหนือ. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปทรงเป็นการจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ซึ่งบรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการจัดรูปแบบเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือ ตั้งชื่อของรูปทรง. ต้องไม่เป็น null. ใช้ค่าว่างหากจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าอีดินิตี้เฉพาะสไลด์ที่ไม่ซ้ำกันซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างมั่นใจจากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พาเรนท์หากรูปทรงถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าพลาส์ฮอลเดอร์สำหรับรูปทรง. คืนค่า null หากรูปทรงไม่มีพลาส์ฮอลเดอร์. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอพาเรนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือ ตั้งค่าคุณสมบัติของกรอบรูปทรงดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือ ตั้งค่าจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z. ค่าเชิงบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเชิงลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อคของรูปทรง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 คุณสมบัติ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเรนท์ของรูปทรง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติ 3d สำหรับรูปทรง. หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | รับทุกร่องรอยที่อยู่ในองค์ประกอบ IInk [`IInkTrace`](../iinktrace). อ่านอย่างเดียว. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าตัวระบุภายในที่กำหนดขอบเขตโดยการนำเสนอซึ่งมุ่งใช้สำหรับแอดอินหรือโค้ดอื่น ๆ. เนื่องจากค่าด่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันอย่างถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปทรง หน่วยเป็นพอยต์. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นพอยต์. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรงในลำดับ z-order. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของ z-order. อ่านอย่างเดียว Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | รับคอลเลกชันของรูปภาพกำหนดเองที่ใช้จำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก. รูปภาพเหล่านี้ใช้เมื่อเรนเดอร์หมึกด้วยค่า [`InkEffectType`](../inkeffecttype) เฉพาะ, เช่น Galaxy, Rainbow, เป็นต้น. โดยการให้รูปภาพของคุณเอง, คุณสามารถควบคุมลักษณะการแสดงผลของแต่ละเอฟเฟกต์หมึก. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มพลาส์ฮอลเดอร์ใหม่หากไม่มีและตั้งค่าคุณสมบัติโพลาส์ฮอลเดอร์ให้กับออบเจ็กต์ที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่าออบเจ็กต์รูปทรงพลาส์ฮอลเดอร์พื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปทรง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปทรง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่พลาส์ฮอลเดอร์. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปทรงเป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject)
* อินเทอร์เฟซ [IInk](../iink)
* เนมสเปซ [Aspose.Slides.Ink](../../aspose.slides.ink)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->