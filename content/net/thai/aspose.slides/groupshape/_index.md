---
title: GroupShape
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงถึงกลุ่มของรูปร่างบนสไลด์หนึ่ง.
type: docs
weight: 5110
url: /th/aspose.slides/groupshape/
---
## GroupShape คลาส

แสดงถึงกลุ่มของรูปร่างบนสไลด์หนึ่ง

```csharp
public class GroupShape : Shape, IGroupShape
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่าหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่างหนึ่ง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่าหรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่างหนึ่ง. อ่าน/เขียน String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | อนุญาตให้ดึงอินเทอร์เฟซ IShape พื้นฐาน. อ่านอย่างเดียว [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะแสดงอย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนอ็อบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนอ็อบเจกต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | คืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนหรือกำหนดลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนผู้จัดการลิงก์ไฮเปอร์. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนหรือกำหนดลิงก์ไฮเปอร์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | ตรวจสอบว่ารูปร่างเป็นส่วนของกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | ตรวจสอบว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | คืนอ็อบเจกต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นของรูปร่าง. หมายเหตุ: คืนค่า null สำหรับอ็อบเจกต์ GroupShape เนื่องจากไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนตัวระบุเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนอ็อบเจกต์ GroupShape แม่ถ้ารูปร่างถูกจัดกลุ่ม. มิฉะนั้นคืน null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนตัวแทนของรูปร่าง. คืน null หากรูปร่างไม่มีตัวแทน. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนหรือกำหนดคุณสมบัติกรอบเฟรมดิบของรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนหรือกำหนดจำนวนองศาที่รูปร่างหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | คืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGroupShapeLock`](../igroupshapelock). (2 properties) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | คืนคอลเลกชันของรูปร่างภายในกลุ่ม. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนอ็อบเจกต์ ThreeDFormat ที่บรรจุคุณสมบัติเอฟเฟกต์ 3 มิติของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในที่สเกลของการนำเสนอซึ่งมักใช้โดยส่วนเสริมหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์คงที่. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่หน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าที่ระบุ |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเค้าโครงและ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมาจาก) หากรูปร่างปัจจุบันไม่ได้สืบทอด จะคืนค่า null |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพย่อของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape จะถูกใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อของรูปร่าง |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG |

### ดูเพิ่มเติม

* คลาส [Shape](../shape)
* อินเทอร์เฟซ [IGroupShape](../igroupshape)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->