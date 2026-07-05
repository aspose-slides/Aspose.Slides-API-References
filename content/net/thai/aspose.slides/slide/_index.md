---
title: Slide
second_title: เอกสารอ้างอิง API ของ Aspose.Sildes สำหรับ .NET
description: เป็นตัวแทนของสไลด์ในงานนำเสนอ.
type: docs
weight: 9960
url: /th/aspose.slides/slide/
---
## คลาส Slide

เป็นตัวแทนของสไลด์ในงานนำเสนอ.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## คุณสมบัติ

| ชื่อ | คำอธิบาย |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | ส่งกลับพื้นหลังของสไลด์. อ่านอย่างเดียว [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | ส่งกลับคอลเลกชันของการควบคุม ActiveX บนสไลด์. อ่านอย่างเดียว [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | ส่งกลับข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | ส่งกลับผู้จัดการ HeaderFooter ของสไลด์. อ่านอย่างเดียว [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | กำหนดว่า สไลด์ที่ระบุถูกซ่อนระหว่างการแสดงสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | ให้การเข้าถึงไฮเปอร์ลิงก์ที่อยู่ภายในอย่างง่าย. อ่านอย่างเดียว [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | ส่งกลับหรือกำหนดสไลด์เค้าโครงสำหรับสไลด์ปัจจุบัน. อ่าน/เขียน [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | ส่งกลับหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | อนุญาตให้เข้าถึงสไลด์โน้ต, เพิ่มและลบ. อ่านอย่างเดียว [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | ส่งกลับอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | ส่งกลับรูปร่างของสไลด์. อ่านอย่างเดียว [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | ระบุว่ารูปร่างบนสไลด์มาสเตอร์ควรแสดงบนสไลด์หรือไม่. อ่าน/เขียน Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | ส่งกลับ ID ของสไลด์. อ่านอย่างเดียว UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | ส่งกลับหมายเลขของสไลด์. ดัชนีของสไลด์ในคอลเลกชัน [`Slides`](../presentation/slides) จะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ. อ่าน/เขียน Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | ส่งกลับอ็อบเจกต์ Transition ซึ่งมีข้อมูลเกี่ยวกับการเปลี่ยนสไลด์ที่ระบุในระหว่างการแสดงสไลด์. อ่านอย่างเดียว [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | ส่งกลับผู้จัดการธีมที่แทนที่. อ่านอย่างเดียว [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | ส่งกลับอ็อบเจกต์ไทม์ไลน์แอนิเมชัน. อ่านอย่างเดียว [`IAnimationTimeLine`](../ianimationtimeline). |

## เมธอด

| ชื่อ | คำอธิบาย |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | ส่งกลับธีมที่มีผลสำหรับสไลด์นี้. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | กำหนดว่าตัวอย่าง IBaseSlide สองอันเท่ากันหรือไม่. ค่าที่ส่งกลับคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่. สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่นๆ ฯลฯ เท่ากัน. การเปรียบเทียบไม่พิจารณาค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าข้อมูลวันที่ปัจจุบันใน Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | ค้นหาการปรากฏแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | ส่งกลับอ็อบเจกต์ Thumbnail Image (ขนาด 20% ของขนาดจริง). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | ส่งกลับอ็อบเจกต์ Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | ส่งกลับอ็อบเจกต์รูปภาพ tiff Thumbnail ด้วยพารามิเตอร์ที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | ส่งกลับอ็อบเจกต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | ส่งกลับอ็อบเจกต์ Thumbnail Image ด้วยการย่อขนาดที่กำหนดเอง. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | ส่งกลับอ็อบเจกต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | ส่งกลับอ็อบเจกต์ Thumbnail Image ด้วยการย่อขนาดที่กำหนดเอง. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | ส่งกลับคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับทั้งหมด. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับทั้งหมด. |
| [Remove](../../aspose.slides/slide/remove)() | ลบสไลด์ออกจากงานนำเสนอ. |
| [Reset](../../aspose.slides/slide/reset)() | รีเซ็ตตำแหน่ง, ขนาดและรูปแบบของทุกรูปร่างที่มีต้นแบบบน LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |

### ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide)
* อินเทอร์เฟซ [ISlide](../islide)
* เนมสเปซ [Aspose.Slides](../../aspose.slides)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->