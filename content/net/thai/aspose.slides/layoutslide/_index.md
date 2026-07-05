---
title: LayoutSlide
second_title: อ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: เป็นตัวแทนของสไลด์เค้าโครง.
type: docs
weight: 7640
url: /th/aspose.slides/layoutslide/
---
## LayoutSlide คลาส

เป็นตัวแทนของสไลด์เค้าโครง.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | คืนค่าพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | คืนค่าคอลเลกชันของควบคุม ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | คืนค่าข้อมูลที่กำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | คืนค่าคอลเลกชันของไกด์การวาดสำหรับสไลด์เค้าโครง. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นกับสไลด์เค้าโครงนี้. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | คืนค่า HeaderFooter manager ของสไลด์เค้าโครง. อ่านอย่างเดียว [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | คืนค่าประเภทเค้าโครงของสไลด์เค้าโครงนี้. อ่านอย่างเดียว [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | คืนค่าหรือกำหนดสไลด์มาสเตอร์สำหรับเค้าโครง. อ่าน/เขียน [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | คืนค่าหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | คืนค่า placeholder manager ของสไลด์เค้าโครง. อ่านอย่างเดียว [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | คืนค่า IPresentation interface. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | คืนค่า shapes ของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | คืนค่า ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | คืนค่า Transition object ที่มีข้อมูลเกี่ยวกับวิธีการที่สไลด์ที่ระบุก้าวหน้าในระหว่างการแสดงสไลด์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | คืนค่า overriding theme manager. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | คืนค่า animation timeline object. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | คืนค่า theme ที่มีประสิทธิภาพสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่คืนคำนวณจากโครงสร้างของสไลด์และเนื้อหาแบบคงที่. สไลด์สองสไลด์เท่ากันถ้ารูปร่าง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่นๆ เป็นต้น ทั้งหมดเท่ากัน. การเปรียบเทียบไม่คำนึงถึงค่าตัวระบุที่ไม่ซ้ำ, เช่น SlideId และเนื้อหาแบบไดนามิก, เช่น ค่าปัจจุบันของวันที่ใน Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการเกิดครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เค้าโครงนี้. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | รวม run ที่มีรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวม run ที่มีรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| [Remove](../../aspose.slides/layoutslide/remove)() | ลบเค้าโครงออกจากการพรีเซนเทชัน. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ILayoutSlide](../ilayoutslide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->