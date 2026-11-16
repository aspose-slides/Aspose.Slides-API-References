---
title: IShape
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงถึงรูปร่างบนสไลด์.
type: docs
weight: 6970
url: /th/aspose.slides/ishape/
---
## อินเทอร์เฟซ IShape

แสดงถึงรูปร่างบนสไลด์.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## คุณสมบัติ

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปทรงหนึ่ง.อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่ที่เชื่อมโยงกับรูปทรงหนึ่ง.อ่าน/เขียน String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | อนุญาตให้ดึงอินเทอร์เฟซฐาน IHyperlinkContainer. อ่านอย่างเดียว [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | อนุญาตให้ดึงอินเทอร์เฟซฐาน ISlideComponent. อ่านอย่างเดียว [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | คุณสมบัตินี้กำหนดว่ารูปทรงจะแสดงผลในโหมดสีดำ-ขาวอย่างไร..อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | คืนค่าอ็อบเจ็กต์ EffectFormat ซึ่งบรรจุเอฟเฟ็กต์พิกเซลที่ใช้กับรูปทรง. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | คืนค่าอ็อบเจ็กต์ FillFormat ที่บรรจุคุณลักษณะการเติมสำหรับรูปทรง. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปทรง.อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | รับ หรือกำหนดความสูงของรูปทรง, วัดเป็นจุด.อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | กำหนดว่ารูปทรงถูกซ่อนหรือไม่.อ่าน/เขียน Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | รับ หรือกำหนดตัวเลือก 'Mark as decorative' .อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | กำหนดว่ารูปทรงอยู่ในกลุ่มหรือไม่.อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่.อ่านอย่างเดียว Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | คืนค่าอ็อบเจ็กต์ LineFormat ที่บรรจุคุณลักษณะการจัดรูปเส้นสำหรับรูปทรง.อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปทรง.อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | คืนค่าออกรหัสประจำตัวที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากที่ใดก็ได้ในเอกสาร.อ่านอย่างเดียว UInt32.ดูเพิ่มเติม [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | คืนค่าอ็อบเจ็กต์ GroupShape พื้นฐานหากรูปทรงอยู่ในกลุ่ม. หากไม่ใช่จะคืนค่า null.อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | คืนค่า placeholder ของรูปทรง.อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของเฟรมรูปทรงดิบ.อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา.อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | คืนค่าการล็อคของรูปทรง.อ่านอย่างเดียว [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่บรรจุคุณลักษณะการจัดรูปเส้นสำหรับรูปทรง.อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | คืนค่าออกรหัสภายในระดับการนำเสนอที่ออกแบบให้ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์เอกลักษณ์ที่คงที่.อ่านอย่างเดียว UInt32.ดูเพิ่มเติม [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | รับ หรือกำหนดความกว้างของรูปทรง, วัดเป็นจุด.อ่าน/เขียน Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | รับ หรือกำหนดพิกัด x ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด.อ่าน/เขียน Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | รับ หรือกำหนดพิกัด y ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด.อ่าน/เขียน Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทร่งที่อยู่ด้านหน้า.อ่านอย่างเดียว Int32. |

## วิธีการ

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder ตามที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | คืนค่า placeholder รูปทรงพื้นฐาน (รูปทรงจากเลย์เอาท์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมา). จะคืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | คืนค่าภาพย่อของรูปทรง. ประเภท ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปทรง. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IHyperlinkContainer](../ihyperlinkcontainer)
* อินเทอร์เฟซ [ISlideComponent](../islidecomponent)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->