---
title: Table
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของตารางบนสไลด์
type: docs
weight: 10860
url: /th/aspose.slides/table/
---
## Table คลาส

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัติกำหนดวิธีที่ shape จะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | คืนค่าคอลเลกชันของคอลัมน์. อ่านอย่างเดียว [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลแบบกำหนดเองของ shape. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่า EffectFormat object ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | คืนค่า TableFormat.FillFormat object ที่มีการจัดรูปแบบการเติมสำหรับ Table. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | กำหนดว่าบรรทัดแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติโฟรมของ shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของ shape. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่า shape ถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | กำหนดว่าบรรทัดคู่ (even rows) ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่า hyperlink manager. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative' . อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | คืนค่าเซลล์ที่ระบุด้วยดัชนีคอลัมน์และแถว. อ่านอย่างเดียว [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | กำหนดว่าบรรทัดสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่า LineFormat object ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า identifier ที่เป็นเอกลักษณ์ในระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่า GroupShape object พาเรนต์หาก shape ถูกจัดกลุ่ม. หากไม่ จะคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของ shape. คืนค่า null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่า presentation พาเรนต์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติโฟรมดิบของ shape. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่ shape หมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | คืนค่าคอลเลกชันของแถว. อ่านอย่างเดียว [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของ shape. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่า slide พาเรนต์ของ shape. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | รับหรือกำหนดสไตล์ตารางในตัว. อ่าน/เขียน [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | คืนค่า TableFormat object ที่มีคุณสมบัติการจัดรูปแบบของตารางนี้. อ่านอย่างเดียว [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่า ThreeDFormat object ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่า identifier ภายในที่ใช้ระดับ presentation สำหรับส่วนเสริมหรือโค้ดอื่น. เนื่องจากค่าที่นี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยการจัดรูปแบบที่แตกต่างหรือไม่. อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของ shape ในลำดับ z-order. Shapes[0] คืนค่า shape ที่สุดท้ายใน z-order, และ Shapes[Shapes.Count - 1] คืนค่า shape ที่หน้าแรกของ z-order. อ่านอย่างเดียว Int32. |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder shape พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์แม่ที่ shape ปัจจุบันสืบทอดมา). คืนค่า null หาก shape ปัจจุบันไม่สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่า thumbnail ของ shape. ใช้ ShapeThumbnailBounds.Shape เป็นประเภทขอบเขต thumbnail เริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่า thumbnail ของ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | รวมเซลล์ใกล้เคียง. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ตั้งค่าคุณสมบัติรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าทั้งหมดของเซลล์ตาราง. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ตั้งค่าคุณสมบัติรูปแบบส่วนที่กำหนดให้กับส่วนทั้งหมดของเซลล์ตาราง. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ตั้งค่าคุณสมบัติรูปแบบกรอบข้อความที่กำหนดให้กับกรอบข้อความของเซลล์ตารางทั้งหมด. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหา Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [ITable](../itable)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->