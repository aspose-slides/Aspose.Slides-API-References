---
title: LayoutSlide
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของเลย์เอาต์สไลด์.
type: docs
weight: 7640
url: /th/aspose.slides/layoutslide/
---
## LayoutSlide คลาส

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## คุณสมบัติ

| Name | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งคืนพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งคืนคอลเลกชันของควบคุม ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | ส่งคืนคอลเลกชันของไกด์การวาดสำหรับเลย์เอาต์สไลด์. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | ส่งคืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับเลย์เอาต์สไลด์นี้. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | ส่งคืนผู้จัดการ HeaderFooter ของเลย์เอาต์สไลด์. อ่านอย่างเดียว [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงลิงก์ไฮเปอร์ลิงก์ที่บรรจุได้อย่างง่ายดาย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | ส่งคืนประเภทเลย์เอาต์ของเลย์เอาต์สไลด์นี้. อ่านอย่างเดียว [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | ส่งคืนหรือกำหนดสไลด์มาสเตอร์สำหรับเลย์เอาต์. อ่าน/เขียน [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | ส่งคืนผู้จัดการ placeholder ของเลย์เอาต์สไลด์. อ่านอย่างเดียว [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งคืนอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งคืนรูปร่างของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งคืน ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งคืนอ็อบเจ็กต์ Transition ซึ่งบรรจุข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุดำเนินการต่อในการนำเสนอ. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | ส่งคืนผู้จัดการธีมที่แทนที่. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งคืนอ็อบเจ็กต์ animation timeline. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## วิธีการ

| Name | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งคืนธีมที่ใช้งานได้สำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่คืนจะคำนวณตามโครงสร้างและเนื้อหาแบบคงที่ของสไลด์. สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหว และการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน. การเปรียบเทียบไม่พิจารณาค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าปัจจุบันของวันที่ใน Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นพบการปรากฏครั้งแรกของรูปร่างที่มีข้อความทางเลือกที่ระบุ. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับเลย์เอาต์สไลด์นี้. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | รวม run ที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวม run ที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด. |
| [Remove](../../aspose.slides/layoutslide/remove)() | ลบเลย์เอาต์ออกจากการนำเสนอ. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ILayoutSlide](../ilayoutslide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->