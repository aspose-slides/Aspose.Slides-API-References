---
title: MasterSlide
second_title: Aspose.Sildes สำหรับ .NET เอกสารอ้างอิง API
description: เป็นตัวแทนของสไลด์มาสเตอร์ในงานนำเสนอ.
type: docs
weight: 8030
url: /th/aspose.slides/masterslide/
---
## MasterSlide คลาส

เป็นตัวแทนของสไลด์มาสเตอร์ในงานนำเสนอ

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งคืนพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | ส่งคืนสไตล์ของข้อความส่วนหลัก. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | ส่งคืนคอลเลกชันของคู่มือการวาดสำหรับสไลด์มาสเตอร์. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | ส่งคืน true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์มาสเตอร์นี้. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์มาสเตอร์. อ่านอย่างเดียว [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบด้วยอย่างง่าย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | ส่งคืนคอลเลกชันของสไลด์เค้าโครงลูกสำหรับสไลด์มาสเตอร์นี้. อ่านอย่างเดียว [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของสไลด์มาสเตอร์. อ่าน/เขียน String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | ส่งคืนสไตล์ของข้อความอื่น. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งคืนอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | กำหนดว่ามาสเตอร์ที่สอดคล้องกันจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามมาจากมาสเตอร์นั้นถูกลบ. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้โดยอัตโนมัติเพื่อให้ลบมาสเตอร์ที่ไม่ได้ใช้จริง ๆ ให้เรียก [`RemoveUnused`](../masterslidecollection/removeunused) อ่าน/เขียน Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งคืนรูปร่างของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. สำหรับสไลด์มาสเตอร์เองคุณสมบัตินี้จะส่งคืน `false` เสมอ. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งคืน ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งคืนวัตถุ Transition ซึ่งมีข้อมูลเกี่ยวกับวิธีที่สไลด์ที่กำหนดก้าวต่อไประหว่างการเปิดสไลด์โชว์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | ส่งคืนผู้จัดการธีม. อ่านอย่างเดียว [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งคืนวัตถุไทม์ไลน์แอนิเมชัน. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | ส่งคืนสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | สร้างสไลด์มาสเตอร์ใหม่โดยอิงจากสไลด์ปัจจุบัน, ประยุกต์ใช้ธีมภายนอกกับมันและนำสไลด์มาสเตอร์ที่สร้างไปใช้กับสไลด์ที่ขึ้นอยู่ทั้งหมด. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งคืนธีมที่มีประสิทธิภาพสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่ส่งกลับจะคำนวณโดยอิงจากโครงสร้างของสไลด์และเนื้อหาคงที่. สไลด์สองสไลด์เท่ากันหากรูปร่าง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน. การเปรียบเทียบไม่คำนึงถึงค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่อยู่ใน Date Placeholder ปัจจุบัน. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการพบครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์มาสเตอร์นี้. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าและรูปร่างที่ยอมรับทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่ยอมรับทั้งหมด. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [IMasterSlide](../imasterslide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->