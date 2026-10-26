---
title: ISlide class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/islide/
---
## ISlide class

แสดงสไลด์หนึ่งในงานนำเสนอ

The ISlide type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/islide/header_footer_manager/) | คืนค่า HeaderFooter manager ของสไลด์<br/>            Read-only [`ISlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/th/aspose.slides/islide/slide_number/) | คืนค่าตัวเลขของสไลด์<br/>            Index of slide in [`IPresentation.slides`](/slides/python-net/th/aspose.slides/ipresentation/slides) collection is always equal to SlideNumber - 1.<br/>            Read/write **int**. |
| [`hidden`](/slides/python-net/th/aspose.slides/islide/hidden/) | กำหนดว่าสไลด์ที่ระบุจะถูกซ่อนระหว่างการแสดงผลหรือไม่<br/>            Read/write **bool**. |
| [`layout_slide`](/slides/python-net/th/aspose.slides/islide/layout_slide/) | คืนค่า หรือ ตั้งค่า layout slide สำหรับสไลด์ปัจจุบัน<br/>            Read/write [`ILayoutSlide`](/slides/python-net/th/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/th/aspose.slides/islide/notes_slide_manager/) | ให้เข้าถึงสไลด์โน้ต เพิ่มและลบสไลด์โน้ตได้<br/>            Read-only [`INotesSlideManager`](/slides/python-net/th/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/th/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/th/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/th/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/th/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/th/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/th/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/th/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/th/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/th/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/th/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/th/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/th/aspose.slides/islide/theme_manager/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/islide/get_image/#float-float) | คืนค่าอ็อบเจ็กต์รูปภาพที่มีการปรับสเกลแบบกำหนดเอง |
| [`get_image(self)`](/slides/python-net/th/aspose.slides/islide/get_image/#) | คืนค่าอ็อบเจ็กต์ Thumbnail Image (ขนาด 20% ของขนาดจริง) |
| [`get_image(self, image_size)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidessize) | คืนค่าอ็อบเจ็กต์รูปภาพที่มีขนาดระบุ |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | คืนค่าอ็อบเจ็กต์ Thumbnail tiff bitmap ที่มีพารามิเตอร์ระบุ |
| [`get_image(self, options)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | คืนค่าอ็อบเจ็กต์ Thumbnail Bitmap |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | คืนค่าอ็อบเจ็กต์ Thumbnail Bitmap ที่มีการปรับสเกลแบบกำหนดเอง |
| [`get_image(self, options, image_size)`](/slides/python-net/th/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | คืนค่าอ็อบเจ็กต์ Thumbnail Bitmap ที่มีขนาดระบุ |
| [`write_as_svg(self, stream)`](/slides/python-net/th/aspose.slides/islide/write_as_svg/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/th/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG |
| [`get_slide_comments(self, author)`](/slides/python-net/th/aspose.slides/islide/get_slide_comments/#icommentauthor) | คืนค่าความคิดเห็นทั้งหมดของสไลด์ที่เพิ่มโดยผู้เขียนเฉพาะ |
| [`write_as_emf(self, stream)`](/slides/python-net/th/aspose.slides/islide/write_as_emf/#iorawiobase) | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF |
| [`remove(self)`](/slides/python-net/th/aspose.slides/islide/remove/#) | ลบสไลด์ออกจากงานนำเสนอ |
| [`reset(self)`](/slides/python-net/th/aspose.slides/islide/reset/#) | รีเซ็ตตำแหน่ง ขนาด และการจัดรูปแบบของทุกรูปทรงที่มีต้นแบบบน LayoutSlide |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/th/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/th/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/th/aspose.slides/islide/create_theme_effective/#) |  |

### ดูเพิ่มเติม
* module [`aspose.slides`](/slides/python-net/th/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)