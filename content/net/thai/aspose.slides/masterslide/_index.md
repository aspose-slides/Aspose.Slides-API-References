---
title: MasterSlide
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: แสดงถึงมาสเตอร์สไลด์ในงานนำเสนอ.
type: docs
weight: 8030
url: /th/aspose.slides/masterslide/
---
## MasterSlide คลาส

แสดงถึงมาสเตอร์สไลด์ในงานนำเสนอ.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งคืนพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | ส่งคืนสไตล์ของข้อความหลัก. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งคืนคอลเลคชันของคอนโทรล ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งคืนข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | ส่งคืนคอลเลคชันของไกด์การวาดสำหรับมาสเตอร์สไลด์. อ่านอย่างเดียว [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | ส่งคืน true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับมาสเตอร์สไลด์นี้. อ่านอย่างเดียว Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | ส่งคืนผู้จัดการ HeaderFooter ของมาสเตอร์สไลด์. อ่านอย่างเดียว [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงลิงก์ที่ฝังอยู่ได้อย่างง่ายดาย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | ส่งคืนคอลเลคชันของสไลด์เลเอาต์เด็กสำหรับมาสเตอร์สไลด์นี้. อ่านอย่างเดียว [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของมาสเตอร์สไลด์. อ่าน/เขียน String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | ส่งคืนสไตล์ของข้อความอื่น. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งคืนอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | กำหนดว่ามาสเตอร์ที่สอดคล้องจะถูกลบหรือไม่เมื่อสไลด์ทั้งหมดที่ตามหลังมาสเตอร์นั้นถูกลบ. หมายเหตุ: Aspose.Slides จะไม่ลบมาสเตอร์ที่ไม่ได้ใช้ใด ๆ ด้วยตนเอง, เพื่อทำการลบมาสเตอร์ที่ไม่ได้ใช้จริง ๆ ให้เรียก [`RemoveUnused`](../masterslidecollection/removeunused) อ่าน/เขียน Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งคืนรูปทรงของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | ระบุว่ารูปทรงบนมาสเตอร์สไลด์ควรแสดงบนสไลด์หรือไม่. สำหรับมาสเตอร์สไลด์เอง property นี้จะส่งคืน `false` เสมอ. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งคืน ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งคืนอ็อบเจ็กต์ Transition ที่มีข้อมูลเกี่ยวกับวิธีการที่สไลด์ที่ระบุจะเคลื่อนที่ต่อไปในระหว่างการแสดงสไลด์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | ส่งคืนผู้จัดการธีม. อ่านอย่างเดียว [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์ของแอนิเมชัน. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | ส่งคืนสไตล์ของข้อความหัวเรื่อง. อ่านอย่างเดียว [`ITextStyle`](../itextstyle). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | สร้างมาสเตอร์สไลด์ใหม่โดยอิงจากมาสเตอร์สไลด์ปัจจุบัน, ใช้ธีมภายนอกกับมันและนำมาสเตอร์สไลด์ที่สร้างไปใช้กับสไลด์ที่ขึ้นอยู่ทั้งหมด. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งคืนธีมที่มีประสิทธิภาพสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide ทั้งสองเท่ากันหรือไม่. ค่าที่คืนถูกคำนวนตามโครงสร้างของสไลด์และเนื้อหาคงที่. สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน. การเปรียบเทียบไม่ได้คำนึงถึงค่าตัวระบุที่ไม่ซ้ำกัน, เช่น SlideId และเนื้อหาแบบไดนามิก, เช่น ค่าปัจจุบันของวันที่ใน Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการปรากฏครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | ส่งคืนอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับมาสเตอร์สไลด์นี้. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปทรงที่ยอมรับทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปทรงที่ยอมรับทั้งหมด. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [IMasterSlide](../imasterslide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซ็มบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->