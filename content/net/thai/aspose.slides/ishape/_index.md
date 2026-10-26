---
title: IShape
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงรูปร่างบนสไลด์.
type: docs
weight: 6950
url: /th/aspose.slides/ishape/
---
## IShape อินเทอร์เฟซ

แสดงถึงรูปร่างบนสไลด์

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความอธิบายภาพที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อของข้อความอธิบายภาพที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | อนุญาตให้รับอินเทอร์เฟซ IHyperlinkContainer พื้นฐาน. อ่านอย่างเดียว [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | อนุญาตให้รับอินเทอร์เฟซ ISlideComponent พื้นฐาน. อ่านอย่างเดียว [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปร่างจะแสดงผลในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | คืนค่าอ็อบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | คืนค่าอ็อบเจกต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีสำหรับรูปร่าง. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' . อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่. อ่านอย่างเดียว Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | คืนค่าอ็อบเจกต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | คืนค่า ID ที่ไม่ซ้ำภายในสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้จากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | คืนค่าอ็อบเจกต์ GroupShape พาเรนท์หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | คืนค่า placeholder ของรูปร่าง. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | คืนค่าอ็อบเจกต์ ThreeDFormat ที่บรรจุคุณสมบัติการจัดรูปเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | คืนค่า ID ภายในที่อยู่ในขอบเขตรายงานเพื่อใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, ไม่ควรถือว่าเป็นคีย์ที่ไม่ซ้ำแบบถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้า. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติ placeholder ให้เป็นค่าที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | คืนรูปร่าง placeholder เบื้องต้น (รูปร่างจากเลเอาต์และ/หรือสไลด์หลักที่รูปร่างปัจจุบันสืบทอดมาจาก). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | คืนภาพย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปร่าง |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IHyperlinkContainer](../ihyperlinkcontainer)
* อินเทอร์เฟซ [ISlideComponent](../islidecomponent)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->