---
title: Slide class
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/slide/
---
## Slide คลาส

แสดงถึงสไลด์ในงานพรีเซนเทชัน.

**การสืบทอด:**[`Slide`](/slides/python-net/th/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)

ประเภท Slide เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/slide/shapes/) | คืนค่า shapes ของสไลด์.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/slide/controls/) | คืนค่าคอลเลกชันของคอนโทรล ActiveX บนสไลด์.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/slide/name/) | คืนค่าหรือกำหนดชื่อของสไลด์.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/slide/slide_id/) | คืนค่า ID ของสไลด์.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/slide/custom_data/) | คืนค่าข้อมูลแบบกำหนดเองของสไลด์.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/slide/timeline/) | คืนค่าอ็อบเจ็กต์ animation timeline.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/slide/slide_show_transition/) | คืนค่าอ็อบเจ็กต์ Transition ซึ่งประกอบด้วยข้อมูลเกี่ยวกับ<br/>            วิธีที่สไลด์ที่ระบุเลื่อนต่อในระหว่างการแสดงสไลด์.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/slide/background/) | คืนค่าพื้นหลังของสไลด์.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/slide/hyperlink_queries/) | ให้การเข้าถึง hyperlink ที่อยู่ภายในอย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/slide/show_master_shapes/) | ระบุว่า shapes บน master slide ควรแสดงบนสไลด์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/slide/presentation/) | คืนค่าอินเทอร์เฟซ IPresentation.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/slide/header_footer_manager/) | คืนค่า HeaderFooter manager ของสไลด์.<br/>            อ่านอย่างเดียว [`ISlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/th/aspose.slides/slide/theme_manager/) | คืนค่า overriding theme manager.<br/>            อ่านอย่างเดียว [`IOverrideThemeManager`](/slides/python-net/th/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/th/aspose.slides/slide/slide_number/) | คืนค่าหมายเลขของสไลด์.<br/>            ดัชนีของสไลด์ในคอลเลกชัน [`Presentation.slides`](/slides/python-net/th/aspose.slides/presentation/slides) จะเท่ากับ SlideNumber - Presentation.FirstSlideNumber เสมอ.<br/>            อ่าน/เขียน **int**. |
| [`hidden`](/slides/python-net/th/aspose.slides/slide/hidden/) | กำหนดว่าระบุสไลด์จะถูกซ่อนหรือไม่ในระหว่างการแสดงสไลด์.<br/>            อ่าน/เขียน **bool**. |
| [`layout_slide`](/slides/python-net/th/aspose.slides/slide/layout_slide/) | คืนค่าหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน.<br/>            อ่าน/เขียน [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/th/aspose.slides/slide/notes_slide_manager/) | อนุญาตให้เข้าถึง notes slide, เพิ่มและลบ.<br/>            อ่านอย่างเดียว [`INotesSlideManager`](/slides/python-net/th/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/th/aspose.slides/slide/slide/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/slide/join_portions_with_same_formatting/#) | เชื่อมต่อ runs ที่มีการจัดรูปแบบเดียวกันในทุก paragraph ในทุก shape ที่ยอมรับได้. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | เชื่อมต่อ runs ที่มีการจัดรูปแบบเดียวกันในทุก paragraph ในทุก shape ที่ยอมรับได้. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/slide/get_image/#float-float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลตามกำหนด. |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/slide/get_image/#) | คืนค่าอ็อบเจ็กต์ Thumbnail Image (20% ของขนาดจริง). |
| [`get_image(self, image_size)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidessize) | คืนค่าอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | คืนค่าอ็อบเจ็กต์ Thumbnail tiff image ด้วยพารามิเตอร์ที่ระบุ. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | คืนค่าอ็อบเจ็กต์ Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image ด้วยการปรับสเกลตามกำหนด. |
| [`get_image(self, options, image_size)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | คืนค่าอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/slide/write_as_svg/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/slide/equals/#ibaseslide) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่.<br/>            ค่าที่คืนคำนวณจากโครงสร้างสไลด์และเนื้อหาคงที่.<br/>            สไลด์สองสไลด์เท่ากันหาก shapes, styles, texts, animation และการตั้งค่าอื่น ๆ เป็นต้น มีค่าเท่ากัน. การเปรียบเทียบไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/slide/create_theme_effective/#) | คืนค่า theme ที่ใช้งานสำหรับสไลด์นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/slide/find_shape_by_alt_text/#str) | ค้นหาการปรากฏครั้งแรกของ shape ที่มี alternative text ที่ระบุ. |
| [`write_as_emf(self, stream)`](/slides/python-net/th/aspose.slides/slide/write_as_emf/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [`remove(self)`](/slides/python-net/th/aspose.slides/slide/remove/#) | ลบสไลด์ออกจากพรีเซนเทชัน. |
| [`reset(self)`](/slides/python-net/th/aspose.slides/slide/reset/#) | รีเซ็ตตำแหน่ง, ขนาด และการจัดรูปแบบของทุก shape ที่มีต้นแบบบน LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/th/aspose.slides/slide/get_slide_comments/#icommentauthor) | คืนค่าคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |


### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`Slide`](/slides/python-net/th/aspose.slides/slide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)