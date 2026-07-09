---
title: Slide
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: แสดงสไลด์ในงานนำเสนอ
type: docs
weight: 9960
url: /th/aspose.slides/slide/
---
## คลาส Slide

แสดงสไลด์หนึ่งในงานนำเสนอ

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งคืนพื้นหลังของสไลด์ อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งคืนชุดของคอนโทรล ActiveX บนสไลด์ อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งคืนข้อมูลแบบกำหนดเองของสไลด์ อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์ อ่านอย่างเดียว [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงสไลด์หรือไม่ อ่าน/เขียน Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงไฮเปอร์ลิงก์ที่อยู่ในสไลด์อย่างง่าย อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | ส่งคืนหรือกำหนดสไลด์เลย์เอาต์สำหรับสไลด์ปัจจุบัน อ่าน/เขียน [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | ส่งคืนหรือกำหนดชื่อของสไลด์ อ่าน/เขียน String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | อนุญาตให้เข้าถึงสไลด์บันทึก เพิ่มและลบสไลด์นี้ได้ อ่านอย่างเดียว [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งคืนอินเทอร์เฟซ IPresentation อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งคืนรูปร่างของสไลด์ อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนมาสเตอร์สไลด์จะแสดงบนสไลด์หรือไม่ อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งคืน ID ของสไลด์ อ่านอย่างเดียว UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | ส่งคืนลำดับของสไลด์ ดัชนีของสไลด์ใน [`Slides`](../presentation/slides) คอลเลกชันจะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ อ่าน/เขียน Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งคืนอ็อบเจ็กต์ Transition ซึ่งมีข้อมูลเกี่ยวกับการเปลี่ยนสไลด์ที่ระบุระหว่างการแสดงสไลด์ อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | ส่งคืนผู้จัดการธีมที่ทำการทับซ้อนอ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์ของแอนิเมชันอ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งคืนธีมที่มีผลสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่ ค่าที่คืนมาจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์ถือว่าเท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ เป็นต้น มีค่าเท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่วันที่ปัจจุบันในตัวแปรแทนวันที่. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | ส่งคืนอ็อบเจ็กต์ Thumbnail Image (ขนาด 20% ของขนาดจริง). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | ส่งคืนอ็อบเจ็กต์รูปภาพ Thumbnail tiff พร้อมพารามิเตอร์ที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลแบบกำหนดเอง. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลแบบกำหนดเอง. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | ส่งคืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รับได้ทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รับได้ทั้งหมด. |
| [Remove](../../aspose.slides/slide/remove)() | ลบสไลด์ออกจากงานนำเสนอ. |
| [Reset](../../aspose.slides/slide/reset)() | รีเซ็ตตำแหน่ง, ขนาด และการจัดรูปแบบของรูปร่างทั้งหมดที่มีต้นแบบบน LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->