---
title: GroupShape
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงกลุ่มของรูปร่างบนสไลด์.
type: docs
weight: 5090
url: /th/aspose.slides/groupshape/
---
## คลาส GroupShape

เป็นตัวแทนของกลุ่มรูปร่างบนสไลด์.

```csharp
public class GroupShape : Shape, IGroupShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความอธิบายทางเลือกที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดชื่อของข้อความอธิบายทางเลือกที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | อนุญาตให้รับพื้นฐาน IShape interface. อ่านอย่างเดียว [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะแสดงในโหมดสีดำ-ขาวอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลที่กำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจส่งค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง. หมายเหตุ: อาจส่งค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของรูปเฟรมของรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | ส่งคืนล็อกของรูปร่าง. อ่านอย่างเดียว [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างหน่วยจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเพอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเพอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเพอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | ส่งคืนอ็อบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: ส่งค่า null สำหรับอ็อบเจกต์ GroupShape เนื่องจากไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างถ้าจำเป็น. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนตัวระบุที่ไม่ซ้ำซึ่งจำกัดอยู่ในสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดในเอกสารได้อย่างเชื่อถือได้. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจกต์ GroupShape พาเรนท์หากรูปร่างถูกจัดกลุ่ม. มิฉะนั้นส่งค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืน placeholder ของรูปร่าง. ส่งค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนพาเรนท์พรีเซนเทชันของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของรูปเฟรมดิบของรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z. ค่าเป็นบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าเป็นลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | ส่งคืนล็อกของรูปร่าง. อ่านอย่างเดียว [`IGroupShapeLock`](../igroupshapelock). (2 properties) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | ส่งคืนคอลเลกชันของรูปร่างภายในกลุ่ม. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนท์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: อาจส่งค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในที่จำกัดอยู่ในพรีเซนเทชันซึ่งใช้สำหรับแอด-อินหรือโค้ดอื่นๆ. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่ไม่ซ้ำกันอย่างถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง หน่วยจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่าง หน่วยจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่าง หน่วยจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] ส่งคืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] ส่งคืนรูปร่างที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน placeholder รูปร่างพื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา). จะคืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืนภาพขนาดเล็กของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพขนาดเล็กของรูปร่าง. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืนภาพขนาดเล็กของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [Shape](../shape)
* อินเทอร์เฟซ [IGroupShape](../igroupshape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->