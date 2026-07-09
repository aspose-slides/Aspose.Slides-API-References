---
title: LegacyDiagram
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แทนวัตถุแผนภูมิดั้งเดิม
type: docs
weight: 7670
url: /th/aspose.slides/legacydiagram/
---
## LegacyDiagram คลาส

แทนวัตถุแผนภูมิดั้งเดิม

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน/เขียน String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | ให้เข้าถึงอินเทอร์เฟซ IGraphicalObject พื้นฐาน อ่านอย่างเดียว [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ อ่าน/เขียน [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนค่าอ็อบเจกต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนค่าอ็อบเจกต์ FillFormat ที่บรรจุคุณสมบัติการเติมสีของรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติกรอบเฟรมของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อคของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | คืนค่าหรือกำหนดความสูงของรูปร่างเป็นจุด อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์สำหรับการคลิกเมาส์ อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนค่าไฮเปอร์ลิงก์เมเนเจอร์ อ่านอย่างเดียว [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์สำหรับการวางเมาส์เหนือรูปร่าง อ่าน/เขียน [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับหรือกำหนดตัวเลือก “ทำเครื่องหมายเป็นของตกแต่ง” อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่ อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนค่าอ็อบเจกต์ LineFormat ที่บรรจุคุณสมบัติการวาดเส้นของรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการวาดเส้น อ่านอย่างเดียว [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่าหรือกำหนดชื่อของรูปร่าง ต้องไม่เป็นค่า null หากต้องการให้เป็นค่าว่างให้ใช้สตริงว่าง อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าไอดีแบบอ้างอิงเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและใช้เพื่ออ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนค่าอ็อบเจกต์ GroupShape พาเรนต์หากรูปร่างเป็นกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืนค่าที่พักของรูปร่าง หากไม่มีที่พักจะคืนค่า null อ่านอย่างเดียว [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนค่าการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่าหรือกำหนดคุณสมบัติกรอบดิบของรูปร่าง อ่าน/เขียน [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่าหรือกำหนดจำนวนองศาที่รูปร่างหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อคของรูปร่าง อ่านอย่างเดียว [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 คุณสมบัติ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนค่าสไลด์พาเรนต์ของรูปร่าง อ่านอย่างเดียว [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนค่าอ็อบเจกต์ ThreeDFormat ที่บรรจุคุณสมบัติ 3d ของรูปร่าง หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3d อ่านอย่างเดียว [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนค่าไอดีภายในระดับการนำเสนอที่ออกแบบให้ใช้โดยแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่าอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | คืนค่าหรือกำหนดความกว้างของรูปร่างเป็นจุด อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | คืนค่าหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่างเป็นจุด อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | คืนค่าหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่างเป็นจุด อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนค่าตำแหน่งของรูปร่างในลำดับ z. Shapes[0] ให้รูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] ให้รูปร่างที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว Int32. |

## Methods

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่มที่พักใหม่หากไม่มีและกำหนดคุณสมบัติของที่พักให้กับที่พักที่ระบุ |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | แปลงแผนภูมิดั้งเดิมเป็นกลุ่มรูปร่างที่แก้ไขได้ วัตถุ GroupShape ที่สร้างขึ้นจะถูกเพิ่มไปยังกลุ่มพาเรนต์ในตำแหน่งเดียวกัน |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | แปลงแผนภูมิดั้งเดิมเป็นอ็อบเจกต์ SmartArt ที่แก้ไขได้ วัตถุ SmartArt ที่สร้างขึ้นจะถูกเพิ่มไปยังกลุ่มพาเรนต์ในตำแหน่งเดียวกัน |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนค่ารูปร่างที่พักพื้นฐาน (รูปร่างจากเลเอาต์หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอด) คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนค่าภาพย่อของรูปร่าง ประเภท ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้น |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนค่าภาพย่อของรูปร่าง |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพที่มองเห็นของรูปร่างที่คำนวณจากเนื้อหาที่แสดงผล |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ที่พัก |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG |

### ดูเพิ่ม

* คลาส [GraphicalObject](../graphicalobject)
* อินเทอร์เฟซ [ILegacyDiagram](../ilegacydiagram)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->