---
title: SmartArt
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงไดอะแกรม SmartArt
type: docs
weight: 10600
url: /th/aspose.slides.smartart/smartart/
---
## คลาส SmartArt

แสดงไดอะแกรม SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | ส่งคืนคอลเลกชันของโหนดทั้งหมดในวัตถุ SmartArt. อ่านอย่างเดียว [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | ส่งคืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | ส่งคืนหรือกำหนดชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดว่ารูปร่างจะแสดงผลในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | ส่งคืนหรือกำหนดสไตล์สีของวัตถุ SmartArt. อ่าน/เขียน [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ส่งคืนอ็อบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | ส่งคืนอ็อบเจกต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | ส่งคืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | ระบุว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ส่งคืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเมาส์โอเวอร์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | ระบุว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | ส่งคืนหรือกำหนดสถานะของไดอะแกรม SmartArt เกี่ยวกับการจัดทิศ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากไดอะแกรมรองรับการพลิก. อ่าน/เขียน Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | ระบุว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | ส่งคืนหรือกำหนดเค้าโครงของวัตถุ SmartArt. อ่าน/เขียน [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | ส่งคืนอ็อบเจกต์ LineFormat ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. อ่าน/เขียน String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | ส่งคืนคอลเลกชันของโหนดรากในวัตถุ SmartArt. อ่านอย่างเดียว [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | ส่งคืนรหัสประจำตัวที่ไม่ซ้ำภายในสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | ส่งคืนอ็อบเจกต์ GroupShape พาเรนต์หากรูปร่างเป็นกลุ่ม มิฉะนั้นจะคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | ส่งคืนตัวแสดงตำแหน่งสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวแสดงตำแหน่ง. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ส่งคืนพรีเซนเทชั่นพาเรนต์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | ส่งคืนหรือกำหนดสไตล์ด่วนของวัตถุ SmartArt. อ่าน/เขียน [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ส่งคืนหรือกำหนดคุณสมบัติกรอบของกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | ส่งคืนหรือกำหนดจำนวนองศาที่รูปร่างกำหนดมุมหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | ส่งคืนการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 คุณสมบัติ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | ส่งคืนสไลด์พาเรนต์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | ส่งคืนอ็อบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติของรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | ส่งคืนตัวระบุภายในแบบสโคปพรีเซนเทชั่นที่ออกแบบมาสำหรับใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรมจึงต้องไม่ถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่างเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | ส่งคืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้กับที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | ส่งคืน placeholder รูปร่างพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอด). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | ส่งคืน thumbnail ของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | ส่งคืน thumbnail ของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวนจากเนื้อหาที่เรนเดอร์. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | ระบุว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject)
* อินเทอร์เฟซ [ISmartArt](../ismartart)
* เนมสเปซ [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->