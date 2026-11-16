---
title: Slide
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงสไลด์ในงานนำเสนอ
type: docs
weight: 9980
url: /th/aspose.slides/slide/
---
## คลาส Slide

แสดงถึงสไลด์ในงานนำเสนอหนึ่งรายการ.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | คืนค่าสีพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | คืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | คืนข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | คืนผู้จัดการ HeaderFooter ของสไลด์. อ่านอย่างเดียว [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | กำหนดว่าสตร์ไลด์ที่ระบุถูกซ่อนในระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงไฮเปอร์ลิงก์ที่มีอยู่ในสไลด์อย่างง่าย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | คืนหรือกำหนดสไลด์แบบเลย์เอาต์สำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | คืนหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | อนุญาตให้เข้าถึงสไลด์โน้ต, เพิ่มและลบโน้ต. อ่านอย่างเดียว [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | คืนอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | คืนรูปทรงของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | ระบุว่ารูปทรงบนสไลด์หลักจะต้องแสดงบนสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | คืน ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | คืนหมายเลขของสไลด์. ดัชนีสไลด์ในคอลเลกชัน [`Slides`](../presentation/slides) จะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ. อ่าน/เขียน Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | คืนอ็อบเจ็กต์ Transition ที่มีข้อมูลเกี่ยวกับการเคลื่อนที่ของสไลด์ที่ระบุในระหว่างการแสดงสไลด์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | คืนผู้จัดการธีมที่แทนที่. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | คืนอ็อบเจ็กต์ไทม์ไลน์แอนิเมชัน. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## วิธีการ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | คืนธีมที่ใช้ได้จริงสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่คืนคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่. สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ เป็นต้นเท่ากัน. การเปรียบเทียบไม่พิจารณาค่าตัวระบุที่ไม่ซ้ำกัน เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการปรากฏตัวแรกของรูปทรงที่มีข้อความสำรองตามที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | คืนอ็อบเจ็กต์ Thumbnail Image (ขนาด 20% ของขนาดจริง). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | คืนอ็อบเจ็กต์ Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | คืนอ็อบเจ็กต์ภาพ Thumbnail tiff พร้อมพารามิเตอร์ที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | คืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | คืนอ็อบเจ็กต์ Thumbnail Image ด้วยการสเกลแบบกำหนดเอง. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | คืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | คืนอ็อบเจ็กต์ Thumbnail Image ด้วยการสเกลแบบกำหนดเอง. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | คืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | รวม run ที่มีการฟอร์แมตเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวม run ที่มีการฟอร์แมตเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| [Remove](../../aspose.slides/slide/remove)() | ลบสไลด์ออกจากงานนำเสนอ. |
| [Reset](../../aspose.slides/slide/reset)() | รีเซ็ตตำแหน่ง, ขนาดและการฟอร์แมตของรูปทรงทุกอันที่มีต้นแบบบน LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->