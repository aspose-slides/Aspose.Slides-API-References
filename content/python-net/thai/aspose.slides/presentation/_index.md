---
title: Presentation class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/presentation/
---
## คลาส Presentation

แสดงถึงการนำเสนอ Microsoft PowerPoint.

ประเภท Presentation เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/presentation/__init__/#) | ตัวสร้างนี้สร้างการนำเสนอใหม่ตั้งแต่ต้น.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [`__init__(self, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#loadoptions) | ตัวสร้างนี้สร้างการนำเสนอใหม่ตั้งแต่ต้น.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [`__init__(self, stream)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่แล้ว. |
| [`__init__(self, stream, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | ตัวสร้างนี้เป็นกลไกหลักสำหรับการอ่าน Presentation ที่มีอยู่แล้ว. |
| [`__init__(self, file)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ซึ่ง<br/>             เนื้อหาของ Presentation ถูกอ่าน. |
| [`__init__(self, file, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str-loadoptions) | ตัวสร้างนี้รับเส้นทางไฟล์ต้นทางที่ซึ่ง<br/>            เนื้อหาของ Presentation ถูกอ่าน. |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`current_date_time`](/slides/python-net/th/aspose.slides/presentation/current_date_time/) | ส่งคืนหรือกำหนดวันที่และเวลาที่จะทดแทนเนื้อหาในฟิลด์ datetime.<br/>            เวลาเริ่มต้นของการสร้างอ็อบเจกต์ Presentation นี้โดยค่าเริ่มต้น.<br/>            อ่าน/เขียน **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/presentation/header_footer_manager/) | ส่งคืนผู้จัดการ HeaderFooter ปัจจุบัน.<br/>            อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](/slides/python-net/th/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/th/aspose.slides/presentation/protection_manager/) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้.<br/>            อ่านอย่างเดียว [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/th/aspose.slides/presentation/slides/) | ส่งคืนรายการของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/th/>            อ่านอย่างเดียว [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/th/aspose.slides/presentation/sections/) | ส่งคืนรายการของส่วนสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISectionCollection`](/slides/python-net/th/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/th/aspose.slides/presentation/slide_size/) | ส่งคืนอ็อบเจกต์ขนาดสไลด์.<br/>            อ่านอย่างเดียว [`ISlideSize`](/slides/python-net/th/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/th/aspose.slides/presentation/notes_size/) | ส่งคืนอ็อบเจกต์ขนาดสไลด์โน้ต.<br/>            อ่านอย่างเดียว [`INotesSize`](/slides/python-net/th/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/th/aspose.slides/presentation/layout_slides/) | ส่งคืนรายการของสไลด์ Layout ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/th/aspose.slides/presentation/masters/) | ส่งคืนรายการของสไลด์ Master ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IMasterSlideCollection`](/slides/python-net/th/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_notes_slide_manager/) | ส่งคืนผู้จัดการโน้ต Master.<br/>            อ่านอย่างเดียว [`IMasterNotesSlideManager`](/slides/python-net/th/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_handout_slide_manager/) | ส่งคืนผู้จัดการ Handout Master.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideManager`](/slides/python-net/th/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/th/aspose.slides/presentation/fonts_manager/) | ส่งคืนผู้จัดการฟอนต์.<br/>            อ่านอย่างเดียว [`IFontsManager`](/slides/python-net/th/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/th/aspose.slides/presentation/default_text_style/) | ส่งคืนสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/th/aspose.slides/presentation/comment_authors/) | ส่งคืนคอลเลกชันของผู้เขียนความคิดเห็น.<br/>            อ่านอย่างเดียว [`ICommentAuthorCollection`](/slides/python-net/th/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/th/aspose.slides/presentation/document_properties/) | ส่งคืนอ็อบเจกต์ DocumentProperties ที่มีคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร.<br/>            อ่านอย่างเดียว [`IDocumentProperties`](/slides/python-net/th/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/th/aspose.slides/presentation/images/) | ส่งคืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IImageCollection`](/slides/python-net/th/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/th/aspose.slides/presentation/audios/) | ส่งคืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IAudioCollection`](/slides/python-net/th/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/th/aspose.slides/presentation/videos/) | ส่งคืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IVideoCollection`](/slides/python-net/th/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/th/aspose.slides/presentation/slide_show_settings/) | ส่งคืนการตั้งค่าสไลด์โชว์สำหรับการนำเสนอ. |
| [`digital_signatures`](/slides/python-net/th/aspose.slides/presentation/digital_signatures/) | ส่งคืนคอลเลกชันของลายเซ็นที่ใช้ลงนามในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IDigitalSignatureCollection`](/slides/python-net/th/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/th/aspose.slides/presentation/custom_data/) | ส่งคืนข้อมูลกำหนดเองของการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/th/aspose.slides/presentation/all_custom_xml_parts/) | ส่งคืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomXmlPart`](/slides/python-net/th/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/th/aspose.slides/presentation/vba_project/) | รับหรือกำหนดโครงการ VBA พร้อมมาโครของการนำเสนอ.<br/>            อ่าน/เขียน [`IVbaProject`](/slides/python-net/th/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/presentation/hyperlink_queries/) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอทั้งหมดอย่างง่าย (ไม่รวมสไลด์ master, layout, notes).<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/th/aspose.slides/presentation/view_properties/) | รับคุณสมบัติวิวแบบครอบคลุมของการนำเสนอ.<br/>            อ่านอย่างเดียว [`IViewProperties`](/slides/python-net/th/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/th/aspose.slides/presentation/first_slide_number/) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [`sensitivity_labels`](/slides/python-net/th/aspose.slides/presentation/sensitivity_labels/) | ส่งคืนคอลเลกชันของป้ายกำหนดความละเอียดอ่อนที่ใช้กับเอกสารการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISensitivityLabelCollection`](/slides/python-net/th/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/th/aspose.slides/presentation/source_format/) | ส่งคืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลดมา.<br/>            อ่านอย่างเดียว [`SourceFormat`](/slides/python-net/th/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/th/aspose.slides/presentation/master_theme/) | ส่งคืนธีม master.<br/>            อ่านอย่างเดียว [`IMasterTheme`](/slides/python-net/th/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/th/aspose.slides/presentation/presentation/) |  |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [`save(self, stream, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุ. |
| [`save(self, fname, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [`save(self, options)`](/slides/python-net/th/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่แสดง XAML markup. |
| [`save(self, fname, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [`save(self, stream, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอไปยังสตรีมในรูปแบบที่ระบุโดยคงหมายเลขหน้า. |
| [`get_images(self, options)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | ส่งคืนอ็อบเจกต์ Image สำหรับสไลด์ทั้งหมดของการนำเสนอ. |
| [`get_images(self, options, slides)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอ. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยการปรับขนาดที่กำหนดเอง. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยการปรับขนาดที่กำหนดเอง. |
| [`get_images(self, options, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | ส่งคืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | ไฮไลท์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | ไฮไลท์ทุกการจับคู่ของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`get_slide_by_id(self, id)`](/slides/python-net/th/aspose.slides/presentation/get_slide_by_id/#int) | ส่งคืน Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/presentation/join_portions_with_same_formatting/#) | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับได้ทั้งหมดในทุกสไลด์. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | ไฮไลท์ทุกการจับคู่ของ regular expression ด้วยสีที่ระบุ. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/presentation/replace_regex/#str-str) | แทนที่ทุกการจับคู่ของ regular expression ด้วยสตริงที่ระบุ. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)