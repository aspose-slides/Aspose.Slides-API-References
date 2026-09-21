---
title: Slide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/slide/
---
## Slide คลาส

แสดงสไลด์ในงานนำเสนอ.

**Inheritance:**[`Slide`](/slides/python-net/th/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)

ประเภท Slide เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`shapes`](/slides/python-net/th/aspose.slides/slide/shapes/) | ส่งคืนรูปทรงของสไลด์.<br/>            อ่านอย่างเดียว [`IShapeCollection`](/slides/python-net/th/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/th/aspose.slides/slide/controls/) | ส่งคืนคอลเลกชันของควบคุม ActiveX บนสไลด์.<br/>            อ่านอย่างเดียว [`IControlCollection`](/slides/python-net/th/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/th/aspose.slides/slide/name/) | ส่งคืนหรือกำหนดชื่อของสไลด์.<br/>            อ่าน/เขียน **str**. |
| [`slide_id`](/slides/python-net/th/aspose.slides/slide/slide_id/) | ส่งคืน ID ของสไลด์.<br/>            อ่านอย่างเดียว **int**. |
| [`custom_data`](/slides/python-net/th/aspose.slides/slide/custom_data/) | ส่งคืนข้อมูลกำหนดเองของสไลด์.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/th/aspose.slides/slide/timeline/) | ส่งคืนอ็อบเจ็กต์ animation timeline.<br/>            อ่านอย่างเดียว [`IAnimationTimeLine`](/slides/python-net/th/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/slide/slide_show_transition/) | ส่งคืนอ็อบเจ็กต์ Transition ที่มีข้อมูลเกี่ยวกับ<br/>            วิธีที่สไลด์ที่ระบุดำเนินต่อในระหว่างการแสดงสไลด์.<br/>            อ่านอย่างเดียว [`ISlideShowTransition`](/slides/python-net/th/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/th/aspose.slides/slide/background/) | ส่งคืนพื้นหลังของสไลด์.<br/>            อ่านอย่างเดียว [`IBackground`](/slides/python-net/th/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/slide/hyperlink_queries/) | ให้การเข้าถึงลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย.<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/slide/show_master_shapes/) | ระบุว่ารูปทรงบน master slide ควรแสดงบนสไลด์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`presentation`](/slides/python-net/th/aspose.slides/slide/presentation/) | ส่งคืนอินเทอร์เฟซ IPresentation.<br/>            อ่านอย่างเดียว [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/slide/header_footer_manager/) | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์.<br/>            อ่านอย่างเดียว [`ISlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/th/aspose.slides/slide/theme_manager/) | ส่งคืนผู้จัดการธีมที่แทนที่.<br/>            อ่านอย่างเดียว [`IOverrideThemeManager`](/slides/python-net/th/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/th/aspose.slides/slide/slide_number/) | ส่งคืนจำนวนของสไลด์.<br/>            ดัชนีของสไลด์ในคอลเลกชัน [`Presentation.slides`](/slides/python-net/th/aspose.slides/presentation/slides) เสมอเท่ากับ SlideNumber - Presentation.FirstSlideNumber.<br/>            อ่าน/เขียน **int**. |
| [`hidden`](/slides/python-net/th/aspose.slides/slide/hidden/) | กำหนดว่สไลด์ที่ระบุถูกซ่อนไว้ระหว่างการแสดงสไลด์หรือไม่.<br/>            อ่าน/เขียน **bool**. |
| [`layout_slide`](/slides/python-net/th/aspose.slides/slide/layout_slide/) | ส่งคืนหรือกำหนด layout slide สำหรับสไลด์ปัจจุบัน.<br/>            อ่าน/เขียน [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/th/aspose.slides/slide/notes_slide_manager/) | อนุญาตให้เข้าถึงสไลด์บันทึก, เพิ่มและลบมัน.<br/>            อ่านอย่างเดียว [`INotesSlideManager`](/slides/python-net/th/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/th/aspose.slides/slide/slide/) |  |

## วิธีการ

| เมธอด | คำอธิบาย |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/slide/join_portions_with_same_formatting/#) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/th/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | รวม runs ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับทั้งหมด. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/slide/get_image/#float-float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่ปรับสเกลตามกำหนด. |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/slide/get_image/#) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image (20% ของขนาดจริง). |
| [`get_image(self, image_size)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposepydrawingsize) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่มีขนาดตามกำหนด. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | ส่งคืนอ็อบเจ็กต์ Thumbnail tiff image ที่มีพารามิเตอร์ตามกำหนด. |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่ปรับสเกลตามกำหนด. |
| [`get_image(self, options, image_size)`](/slides/python-net/th/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ที่มีขนาดตามกำหนด. |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/slide/write_as_svg/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/slide/equals/#ibaseslide) | กำหนดว่าตัวอย่าง IBaseSlide สองอันเท่ากันหรือไม่.<br/>            ค่าที่ส่งคืนคำนวณจากโครงสร้างสไลด์และเนื้อหาคงที่.<br/>            สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน. การเปรียบเทียบไม่ได้พิจารณาค่าตัวระบุเฉพาะเช่น SlideId และเนื้อหาแบบไดนามิกเช่นค่าปัจจุบันของวันที่ใน Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/slide/create_theme_effective/#) | ส่งคืนธีมที่มีผลสำหรับสไลด์นี้. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/slide/find_shape_by_alt_text/#str) | ค้นหาการปรากฏครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| [`write_as_emf(self, stream)`](/slides/python-net/th/aspose.slides/slide/write_as_emf/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| [`remove(self)`](/slides/python-net/th/aspose.slides/slide/remove/#) | ลบสไลด์ออกจากงานนำเสนอ. |
| [`reset(self)`](/slides/python-net/th/aspose.slides/slide/reset/#) | รีเซ็ตตำแหน่ง, ขนาดและการจัดรูปแบบของทุกรูปทรงที่มีต้นแบบบน LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/th/aspose.slides/slide/get_slide_comments/#icommentauthor) | ส่งคืนคอมเมนต์สไลด์ทั้งหมดที่เพิ่มโดยผู้เขียนเฉพาะ. |

### ดูเพิ่มเติม
* คลาส [`BaseSlide`](/slides/python-net/th/aspose.slides/baseslide)
* คลาส [`Slide`](/slides/python-net/th/aspose.slides/slide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)