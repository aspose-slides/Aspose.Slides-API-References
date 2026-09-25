---
title: Presentation class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides/presentation/
---
## คลาส Presentation

แสดงถึงการนำเสนอของ Microsoft PowerPoint

ประเภท Presentation เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/presentation/__init__/#) | คอนสตรัคเตอร์นี้สร้างการนำเสนอใหม่จากศูนย์.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่าเดียว |
| [`__init__(self, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#loadoptions) | คอนสตรัคเตอร์นี้สร้างการนำเสนอใหม่จากศูนย์.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่าเดียว |
| [`__init__(self, stream)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับอ่าน Presentation ที่มีอยู่ |
| [`__init__(self, stream, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | คอนสตรัคเตอร์นี้เป็นกลไกหลักสำหรับอ่าน Presentation ที่มีอยู่ |
| [`__init__(self, file)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางจากที่<br/>             เนื้อหาของ Presentation ถูกอ่าน |
| [`__init__(self, file, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str-loadoptions) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางจากที่<br/>            เนื้อหาของ Presentation ถูกอ่าน |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`current_date_time`](/slides/python-net/th/aspose.slides/presentation/current_date_time/) | คืนค่า หรือ กำหนด วันที่และเวลา ที่จะแทนที่เนื้อหาของฟิลด์ datetime.<br/>            เวลาในการสร้างวัตถุ Presentation นี้เป็นค่าเริ่มต้น.<br/>            อ่าน/เขียน **System.DateTime** |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/presentation/header_footer_manager/) | คืนค่า HeaderFooter manager ที่ใช้งานจริง.<br/>            อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](/slides/python-net/th/aspose.slides/ipresentationheaderfootermanager) |
| [`protection_manager`](/slides/python-net/th/aspose.slides/presentation/protection_manager/) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอนี้.<br/>            อ่านอย่างเดียว [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager) |
| [`slides`](/slides/python-net/th/aspose.slides/presentation/slides/) | คืนค่ารายการของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/th/>            อ่านอย่างเดียว [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection) |
| [`sections`](/slides/python-net/th/aspose.slides/presentation/sections/) | คืนค่ารายการของส่วนสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISectionCollection`](/slides/python-net/th/aspose.slides/isectioncollection) |
| [`slide_size`](/slides/python-net/th/aspose.slides/presentation/slide_size/) | คืนค่าออ็อบเจ็กต์ขนาดสไลด์.<br/>            อ่านอย่างเดียว [`ISlideSize`](/slides/python-net/th/aspose.slides/islidesize) |
| [`notes_size`](/slides/python-net/th/aspose.slides/presentation/notes_size/) | คืนค่าออ็อบเจ็กต์ขนาดสไลด์บันทึกย่อ.<br/>            อ่านอย่างเดียว [`INotesSize`](/slides/python-net/th/aspose.slides/inotessize) |
| [`layout_slides`](/slides/python-net/th/aspose.slides/presentation/layout_slides/) | คืนค่ารายการของสไลด์เลเอาท์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection) |
| [`masters`](/slides/python-net/th/aspose.slides/presentation/masters/) | คืนค่ารายการของสไลด์มาสเตอร์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IMasterSlideCollection`](/slides/python-net/th/aspose.slides/imasterslidecollection) |
| [`master_notes_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_notes_slide_manager/) | คืนค่า notes master manager.<br/>            อ่านอย่างเดียว [`IMasterNotesSlideManager`](/slides/python-net/th/aspose.slides/imasternotesslidemanager) |
| [`master_handout_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_handout_slide_manager/) | คืนค่า handout master manager.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideManager`](/slides/python-net/th/aspose.slides/imasterhandoutslidemanager) |
| [`fonts_manager`](/slides/python-net/th/aspose.slides/presentation/fonts_manager/) | คืนค่า fonts manager.<br/>            อ่านอย่างเดียว [`IFontsManager`](/slides/python-net/th/aspose.slides/ifontsmanager) |
| [`default_text_style`](/slides/python-net/th/aspose.slides/presentation/default_text_style/) | คืนค่าแบบข้อความเริ่มต้นสำหรับ shapes.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle) |
| [`comment_authors`](/slides/python-net/th/aspose.slides/presentation/comment_authors/) | คืนค่าคอลเลกชันของผู้เขียนความคิดเห็น.<br/>            อ่านอย่างเดียว [`ICommentAuthorCollection`](/slides/python-net/th/aspose.slides/icommentauthorcollection) |
| [`document_properties`](/slides/python-net/th/aspose.slides/presentation/document_properties/) | คืนค่าออ็อบเจ็กต์ DocumentProperties ที่บรรจุคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร.<br/>            อ่านอย่างเดียว [`IDocumentProperties`](/slides/python-net/th/aspose.slides/idocumentproperties) |
| [`images`](/slides/python-net/th/aspose.slides/presentation/images/) | คืนค่าคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IImageCollection`](/slides/python-net/th/aspose.slides/iimagecollection) |
| [`audios`](/slides/python-net/th/aspose.slides/presentation/audios/) | คืนค่าคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IAudioCollection`](/slides/python-net/th/aspose.slides/iaudiocollection) |
| [`videos`](/slides/python-net/th/aspose.slides/presentation/videos/) | คืนค่าคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IVideoCollection`](/slides/python-net/th/aspose.slides/ivideocollection) |
| [`slide_show_settings`](/slides/python-net/th/aspose.slides/presentation/slide_show_settings/) | คืนค่าการตั้งค่าการแสดงสไลด์สำหรับการนำเสนอ |
| [`digital_signatures`](/slides/python-net/th/aspose.slides/presentation/digital_signatures/) | คืนค่าคอลเลกชันของลายเซ็นที่ใช้ในการเซ็นการนำเสนอ.<br/>            อ่านอย่างเดียว [`IDigitalSignatureCollection`](/slides/python-net/th/aspose.slides/idigitalsignaturecollection) |
| [`custom_data`](/slides/python-net/th/aspose.slides/presentation/custom_data/) | คืนค่าข้อมูลกำหนดเองของการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata) |
| [`all_custom_xml_parts`](/slides/python-net/th/aspose.slides/presentation/all_custom_xml_parts/) | คืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomXmlPart`](/slides/python-net/th/aspose.slides/icustomxmlpart)[] |
| [`vba_project`](/slides/python-net/th/aspose.slides/presentation/vba_project/) | รับหรือกำหนดโครงการ VBA ที่มีแมโครของการนำเสนอ.<br/>            อ่าน/เขียน [`IVbaProject`](/slides/python-net/th/aspose.slides.vba/ivbaproject) |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/presentation/hyperlink_queries/) | ให้การเข้าถึงที่ง่ายต่อไฮเปอร์ลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอทั้งหมด (ไม่รวมในมาสเตอร์, เลเอาท์, สไลด์บันทึกย่อ).<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries) |
| [`view_properties`](/slides/python-net/th/aspose.slides/presentation/view_properties/) | รับคุณสมบัติมุมมองทั่วการนำเสนอ.<br/>            อ่านอย่างเดียว [`IViewProperties`](/slides/python-net/th/aspose.slides/iviewproperties) |
| [`first_slide_number`](/slides/python-net/th/aspose.slides/presentation/first_slide_number/) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [`sensitivity_labels`](/slides/python-net/th/aspose.slides/presentation/sensitivity_labels/) | คืนค่าคอลเลกชันของป้ายกำกับความละเอียดอ่อนที่ใช้กับเอกสารการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISensitivityLabelCollection`](/slides/python-net/th/aspose.slides/isensitivitylabelcollection) |
| [`source_format`](/slides/python-net/th/aspose.slides/presentation/source_format/) | คืนข้อมูลเกี่ยวกับรูปแบบที่การนำเสนอถูกโหลดจาก.<br/>            อ่านอย่างเดียว [`SourceFormat`](/slides/python-net/th/aspose.slides/sourceformat) |
| [`master_theme`](/slides/python-net/th/aspose.slides/presentation/master_theme/) | คืนค่า master theme.<br/>            อ่านอย่างเดียว [`IMasterTheme`](/slides/python-net/th/aspose.slides.theme/imastertheme) |
| [`presentation`](/slides/python-net/th/aspose.slides/presentation/presentation/) |  |

## วิธีการ

| วิธีการ | คำอธิบาย |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงไฟล์ในรูปแบบที่กำหนด |
| [`save(self, stream, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงสตรีมในรูปแบบที่กำหนด |
| [`save(self, fname, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงสตรีมในรูปแบบที่กำหนดพร้อมตัวเลือกเพิ่มเติม |
| [`save(self, options)`](/slides/python-net/th/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็น XAML markup |
| [`save(self, fname, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ในรูปแบบที่กำหนดโดยคงหมายเลขหน้า |
| [`save(self, fname, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ในรูปแบบที่กำหนดโดยคงหมายเลขหน้า |
| [`save(self, stream, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอลงสตรีมในรูปแบบที่กำหนดโดยคงหมายเลขหน้า |
| [`save(self, stream, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอลงสตรีมในรูปแบบที่กำหนดโดยคงหมายเลขหน้า |
| [`get_images(self, options)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | คืนค่า Image objects สำหรับสไลด์ทั้งหมดของการนำเสนอ |
| [`get_images(self, options, slides)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | คืนค่า Thumbnail Image objects สำหรับสไลด์ที่ระบุของการนำเสนอ |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | คืนค่า Thumbnail Image objects สำหรับสไลด์ทั้งหมดของการนำเสนอโดยมีการสเกลแบบกำหนดเอง |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | คืนค่า Thumbnail Image objects สำหรับสไลด์ที่ระบุของการนำเสนอโดยมีการสเกลแบบกำหนดเอง |
| [`get_images(self, options, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | คืนค่า Thumbnail Image objects สำหรับสไลด์ทั้งหมดของการนำเสนอโดยมีขนาดที่ระบุ |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | คืนค่า Thumbnail Image objects สำหรับสไลด์ที่ระบุของการนำเสนอโดยมีขนาดที่ระบุ |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | ไฮไลท์การตรงกันทั้งหมดของข้อความตัวอย่างด้วยสีที่กำหนด |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | ไฮไลท์การตรงกันทั้งหมดของข้อความตัวอย่างด้วยสีที่กำหนด |
| [`get_slide_by_id(self, id)`](/slides/python-net/th/aspose.slides/presentation/get_slide_by_id/#int) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/presentation/join_portions_with_same_formatting/#) | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในทุก shape ที่รับได้ในทุกสไลด์ |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | ไฮไลท์การตรงกันทั้งหมดของ regular expression ด้วยสีที่กำหนด |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่การเกิดขึ้นทั้งหมดของข้อความที่กำหนดด้วยข้อความอื่นที่กำหนด |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/presentation/replace_regex/#str-str) | แทนที่การตรงกันทั้งหมดของ regular expression ด้วยสตริงที่กำหนด |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)