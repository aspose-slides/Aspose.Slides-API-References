---
title: MasterSlide
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: เป็นตัวแทนของสไลด์มาสเตอร์ในงานนำเสนอ.
type: docs
weight: 8050
url: /th/aspose.slides/masterslide/
---
## MasterSlide คลาส

Represents a master slide in a presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งคืนพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | ส่งคืนสไตล์ของข้อความหลัก. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | ส่งคืนคอลเลกชันของไกด์การวาดสำหรับมาสเตอร์สไลด์. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | ส่งคืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่พึ่งพามาสเตอร์สไลด์นี้. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | ส่งคืนตัวจัดการ HeaderFooter ของมาสเตอร์สไลด์. อ่านอย่างเดียว [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงลิงก์ภายในอย่างง่ายดาย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | ส่งคืนคอลเลกชันของสไลด์เลย์เอาต์ลูกสำหรับมาสเตอร์สไลด์นี้. อ่านอย่างเดียว [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของมาสเตอร์สไลด์. อ่าน/เขียน String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | ส่งคืนสไตล์ของข้อความอื่น. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งคืนอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | กำหนดว่ามาสเตอร์ที่เกี่ยวข้องจะถูกลบเมื่อสไลด์ทั้งหมดที่ตามมาหลังจากมาสเตอร์นั้นถูกลบหรือไม่. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้โดยตัวเอง, เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริง ให้เรียก [`RemoveUnused`](../masterslidecollection/removeunused) อ่าน/เขียน Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งคืนรูปร่างของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนมาสเตอร์สไลด์ควรแสดงบนสไลด์หรือไม่. สำหรับมาสเตอร์สไลด์เองคุณสมบัตินี้จะส่งคืน `false` เสมอ. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งคืน ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งคืนอ็อบเจกต์ Transition ที่มีข้อมูลเกี่ยวกับวิธีการเปลี่ยนสไลด์ที่กำหนดระหว่างการแสดงสไลด์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | ส่งคืนตัวจัดการธีม. อ่านอย่างเดียว [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งคืนอ็อบเจกต์ไทม์ไลน์ของแอนิเมชัน. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | ส่งคืนสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | สร้างมาสเตอร์สไลด์ใหม่โดยอิงจากมาสเตอร์สไลด์ปัจจุบัน, ทำการใช้ธีมภายนอกกับมันและนำมาสเตอร์สไลด์ที่สร้างไปใช้กับสไลด์ที่ขึ้นต่อมาทั้งหมด. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งคืนธีมที่มีประสิทธิภาพสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่าเทียมกันหรือไม่. ค่าที่ส่งกลับถูกคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่. สไลด์สองอันเท่าเทียมกันหากรูปร่าง, สไตล์, ข้อความ, แอนิเมชัน และการตั้งค่าอื่น ๆ ฯลฯ ทั้งหมดเท่ากัน. การเปรียบเทียบไม่ได้คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าปัจจุบันของวันที่ในตัวแทนวันที่. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการพบครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นต่อมามาสเตอร์สไลด์นี้. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [IMasterSlide](../imasterslide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->