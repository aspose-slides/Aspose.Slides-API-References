---
title: Ink
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: แสดงอ็อบเจกต์หมึกบนสไลด์.
type: docs
weight: 7550
url: /th/aspose.slides.ink/ink/
---
## คลาส Ink

แสดงอ็อบเจกต์หมึกบนสไลด์.

```csharp
public class Ink : GraphicalObject, IInk
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | คืนค่า หรือกำหนดข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | คืนค่า หรือกำหนดชื่อเรื่องของข้อความอธิบายทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | คุณสมบัตินี้ระบุว่ารูปร่างจะแสดงอย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | คืนจำนวนตำแหน่งเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | คืนข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | คืนวัตถุ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | คืนวัตถุ FillFormat ที่บรรจุคุณสมบัติการกำหนดรูปแบบการเติมสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่าง. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | รับ หรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | กำหนดว่ารูปร่างซ่อนอยู่หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | คืนตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | คืนค่า หรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการชี้เมาส์. อ่าน/เขียน [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | รับ หรือกำหนดตัวเลือก 'ทำเครื่องหมายว่าเป็นของตกแต่ง' อ่าน/เขียน Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | คืนวัตถุ LineFormat ที่บรรจุคุณสมบัติการกำหนดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | คืนค่า หรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากต้องการ. อ่าน/เขียน String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | คืนค่าตัวระบุที่ไม่ซ้ำกันในระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสารอย่างเชื่อถือได้. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | คืนวัตถุ GroupShape พาร์เอนท์หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | คืน placeholder สำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | คืนพรีเซนเทชันพาร์เอนท์ของสไลด์. อ่านอย่างเดียว [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | คืนค่า หรือกำหนดคุณสมบัติของกรอบรูปร่างดิบ. อ่าน/เขียน [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | คืนสไลด์พาร์เอนท์ของรูปร่าง. อ่านอย่างเดียว [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | คืนวัตถุ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของรูปร่างที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | รับทุกรอยเส้นที่อยู่ในองค์ประกอบ IInk [`IInkTrace`](../iinktrace). อ่านอย่างเดียว. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | คืนตัวระบุภายในระดับพรีเซนเทชันที่มีจุดประสงค์เพื่อใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันอย่างถาวร. อ่านอย่างเดียว UInt32. ดูเพิ่มเติม [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | รับ หรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | รับ หรือกำหนดพิกัด x ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | รับ หรือกำหนดพิกัด y ของมุมบนซ้ายของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | รับชุดของรูปภาพกำหนดเองที่ใช้เพื่อจำลองเอฟเฟกต์ภาพสำหรับแปรงหมึก. รูปภาพเหล่านี้ใช้เมื่อเรนเดอร์หมึกกับค่า [`InkEffectType`](../inkeffecttype) เฉพาะ, เช่น Galaxy, Rainbow ฯลฯ. โดยการให้รูปภาพของคุณเอง, คุณสามารถควบคุมลักษณะของแต่ละเอฟเฟกต์หมึกได้. |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | เพิ่ม placeholder ใหม่หากไม่มีและกำหนดคุณสมบัติของ placeholder เป็นค่าที่ระบุ. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์หลักที่รูปร่างปัจจุบันสืบทอดมา). คืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด. |
| [GetImage](../../aspose.slides/shape/getimage)() | คืนภาพย่อของรูปร่าง. ประเภท ShapeThumbnailBounds.Shape ใช้เป็นค่าเริ่มต้นสำหรับขอบเขตภาพย่อ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | คืนภาพย่อของรูปร่าง. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์แล้ว. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | บันทึกเนื้อหาของรูปร่างเป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject)
* อินเทอร์เฟซ [IInk](../iink)
* เนมสเปซ [Aspose.Slides.Ink](../../aspose.slides.ink)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->