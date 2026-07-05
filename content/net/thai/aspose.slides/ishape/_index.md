---
title: IShape
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: แสดงถึงรูปร่างบนสไลด์หนึ่ง.
type: docs
weight: 6950
url: /th/aspose.slides/ishape/
---
## IShape อินเทอร์เฟซ

แสดงถึงรูปร่างบนสไลด์.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | อนุญาตให้รับอินเทอร์เฟซฐาน IHyperlinkContainer. อ่านอย่างเดียว [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซฐาน ISlideComponent. อ่านอย่างเดียว [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดวิธีการแสดงรูปร่างในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | คืนข้อมูลที่กำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | คืนอ็อบเจ็กต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | คืนอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปร่าง. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง หน่วยเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'ทำเครื่องหมายว่าเป็นของตกแต่ง' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่. อ่านอย่างเดียว Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | คืนอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ที่คงที่ตลอดช่วงชีวิตของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างน่าเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | คืนอ็อบเจ็กต์ GroupShape พ่อแม่หากรูปร่างถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | คืนตัวแสดงตำแหน่ง (placeholder) สำหรับรูปร่าง. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | คืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | คืนอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | คืนตัวระบุภายในที่จำกัดขอบเขตการนำเสนอซึ่งตั้งไว้สำหรับใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำแบบถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง หน่วยเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นจุด. อ่าน/เขียน Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, ส่วน Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมาจาก). จะคืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | คืนภาพย่อของรูปร่าง. ประเภท ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปร่าง |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISSVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IHyperlinkContainer](../ihyperlinkcontainer)
* อินเทอร์เฟซ [ISlideComponent](../islidecomponent)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->