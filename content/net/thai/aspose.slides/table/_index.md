---
title: Table
second_title: Aspose.Sildes สำหรับ .NET การอ้างอิง API
description: เป็นตัวแทนของตารางบนสไลด์หนึ่ง
type: docs
weight: 10860
url: /th/aspose.slides/table/
---
## Table คลาส

เป็นตัวแทนของตารางบนสไลด์หนึ่ง

```csharp
public sealed class Table : GraphicalObject, ITable
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | คืนค่า ชุดของคอลัมน์. อ่านอย่างเดียว [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลแบบกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่า EffectFormat object ที่ประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | คืนค่า TableFormat.FillFormat object ที่มีการจัดรูปแบบการเติมสำหรับ Table. อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับหรือกำหนดความสูงของรูปร่าง หน่วยเป็นพิกัดจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | กำหนดว่าแถวเลขคูต้องวาดด้วยการจัดรูปแบบที่ต่างกันหรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่า hyperlink manager. อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนด hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก 'Mark as decorative'. อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | คืนค่าเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ. อ่านอย่างเดียว [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่. อ่าน/เขียน Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่า LineFormat object ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่า string ว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่า identifier ที่เป็นเอกลักษณ์ภายในสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและช่วยให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากส่วนใดส่วนหนึ่งของเอกสารได้อย่างเชื่อถือ. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่า GroupShape object แม่ถ้ารูปร่างอยู่ในกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่า placeholder ของรูปร่าง. คืนค่า null ถ้ารูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่า presentation แม่ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่างแบบ raw. อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่. อ่าน/เขียน Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | คืนค่าชุดของแถว. อ่านอย่างเดียว [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่า slide แม่ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | รับหรือกำหนดสไตล์ตารางในตัว. อ่าน/เขียน [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | คืนค่า TableFormat object ที่มีคุณสมบัติการจัดรูปแบบสำหรับตารางนี้. อ่านอย่างเดียว [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่า ThreeDFormat object ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่า identifier ภายในที่กำหนดขอบเขตภายในงานนำเสนอสำหรับใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่าตัวนี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, ไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | กำหนดว่าคอลัมน์คี่ต้องวาดด้วยการจัดรูปแบบที่ต่างกันหรือไม่. อ่าน/เขียน Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับหรือกำหนดความกว้างของรูปร่าง หน่วยเป็นพิกัดจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพิกัดจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพิกัดจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนค่ารูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่อยู่ด้านหน้า. อ่านอย่างเดียว Int32. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับอันที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่า placeholder shape พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือมาสเตอร์สไลด์ที่รูปร่างปัจจุบันสืบทอดมา). จะคืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่า thumbnail ของรูปร่าง. ชนิด ShapeThumbnailBounds.Shape ถูกใช้เป็นค่าเริ่มต้น. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่า thumbnail ของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | ผสานเซลล์ใกล้เคียง. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | ตั้งค่าคุณสมบัติรูปแบบย่อหน้าให้กับย่อหน้าของทุกเซลล์ในตาราง. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | ตั้งค่าคุณสมบัติรูปแบบส่วนให้กับส่วนทั้งหมดของเซลล์ในตาราง. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | ตั้งค่าคุณสมบัติรูปแบบกรอบข้อความให้กับกรอบข้อความของทุกเซลล์ในตาราง. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [ITable](../itable)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->