---
title: Presentation class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/presentation/
---
## Presentation คลาส

เป็นการนำเสนอของ Microsoft PowerPoint

ประเภท Presentation มีสมาชิกต่อไปนี้:

## คอนสตรัคเตอร์

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/presentation/__init__/#) | คอนสตรัคเตอร์นี้สร้างการนำเสนอใหม่ตั้งแต่เริ่มต้น.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [`__init__(self, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#loadoptions) | คอนสตรัคเตอร์นี้สร้างการนำเสนอใหม่ตั้งแต่เริ่มต้น.<br/>            การนำเสนอที่สร้างมีสไลด์เปล่า 1 แผ่น. |
| [`__init__(self, stream)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase) | คอนสตรัคเตอร์นี้เป็นวิธีหลักในการอ่าน Presentation ที่มีอยู่แล้ว. |
| [`__init__(self, stream, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | คอนสตรัคเตอร์นี้เป็นวิธีหลักในการอ่าน Presentation ที่มีอยู่แล้ว. |
| [`__init__(self, file)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่<br/>             เนื้อหาของ Presentation ถูกอ่าน. |
| [`__init__(self, file, load_options)`](/slides/python-net/th/aspose.slides/presentation/__init__/#str-loadoptions) | คอนสตรัคเตอร์นี้รับเส้นทางไฟล์ต้นทางที่<br/>            เนื้อหาของ Presentation ถูกอ่าน. |

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/th/aspose.slides/presentation/current_date_time/) | คืนค่าหรือกำหนดวันที่และเวลาที่จะใช้แทนเนื้อหาของฟิลด์ datetime.<br/>            เวลาในการสร้างอ็อบเจกต์ Presentation นี้ตามค่าเริ่มต้น.<br/>            อ่าน/เขียน **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/presentation/header_footer_manager/) | คืนค่า HeaderFooter manager ปัจจุบัน.<br/>            อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](/slides/python-net/th/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/th/aspose.slides/presentation/protection_manager/) | รับผู้จัดการสิทธิ์สำหรับการนำเสนอครั้งนี้.<br/>            อ่านอย่างเดียว [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/th/aspose.slides/presentation/slides/) | คืนค่ารายการของสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/th/>            อ่านอย่างเดียว [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/th/aspose.slides/presentation/sections/) | คืนค่ารายการของส่วนสไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISectionCollection`](/slides/python-net/th/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/th/aspose.slides/presentation/slide_size/) | คืนค่าอ็อบเจกต์ขนาดสไลด์.<br/>            อ่านอย่างเดียว [`ISlideSize`](/slides/python-net/th/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/th/aspose.slides/presentation/notes_size/) | คืนค่าอ็อบเจกต์ขนาดสไลด์โน้ต.<br/>            อ่านอย่างเดียว [`INotesSize`](/slides/python-net/th/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/th/aspose.slides/presentation/layout_slides/) | คืนค่ารายการของสไลด์เลเอาต์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/th/aspose.slides/presentation/masters/) | คืนค่ารายการของมาสเตอร์สไลด์ทั้งหมดที่กำหนดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IMasterSlideCollection`](/slides/python-net/th/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_notes_slide_manager/) | คืนค่าโน้ตมาสเตอร์เมเนเจอร์.<br/>            อ่านอย่างเดียว [`IMasterNotesSlideManager`](/slides/python-net/th/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/th/aspose.slides/presentation/master_handout_slide_manager/) | คืนค่า handout มาสเตอร์เมเนเจอร์.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideManager`](/slides/python-net/th/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/th/aspose.slides/presentation/fonts_manager/) | คืนค่าเมเนเจอร์ฟอนต์.<br/>            อ่านอย่างเดียว [`IFontsManager`](/slides/python-net/th/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/th/aspose.slides/presentation/default_text_style/) | คืนค่าสไตล์ข้อความเริ่มต้นสำหรับรูปร่าง.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/th/aspose.slides/presentation/comment_authors/) | คืนคอลเลกชันของผู้เขียนความคิดเห็น.<br/>            อ่านอย่างเดียว [`ICommentAuthorCollection`](/slides/python-net/th/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/th/aspose.slides/presentation/document_properties/) | คืนค่าอ็อบเจกต์ DocumentProperties ที่บรรจุคุณสมบัติมาตรฐานและกำหนดเองของเอกสาร.<br/>            อ่านอย่างเดียว [`IDocumentProperties`](/slides/python-net/th/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/th/aspose.slides/presentation/images/) | คืนคอลเลกชันของรูปภาพทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IImageCollection`](/slides/python-net/th/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/th/aspose.slides/presentation/audios/) | คืนคอลเลกชันของไฟล์เสียงฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IAudioCollection`](/slides/python-net/th/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/th/aspose.slides/presentation/videos/) | คืนคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`IVideoCollection`](/slides/python-net/th/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/th/aspose.slides/presentation/slide_show_settings/) | คืนค่าการตั้งค่าแสดงสไลด์สำหรับการนำเสนอ. |
| [`digital_signatures`](/slides/python-net/th/aspose.slides/presentation/digital_signatures/) | คืนคอลเลกชันของลายเซ็นที่ใช้ในการลงนามการนำเสนอ.<br/>            อ่านอย่างเดียว [`IDigitalSignatureCollection`](/slides/python-net/th/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/th/aspose.slides/presentation/custom_data/) | คืนข้อมูลกำหนดเองของการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/th/aspose.slides/presentation/all_custom_xml_parts/) | คืนส่วนข้อมูลกำหนดเองทั้งหมดในการนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomXmlPart`](/slides/python-net/th/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/th/aspose.slides/presentation/vba_project/) | รับหรือกำหนดโปรเจกต์ VBA ที่มีแมโครการนำเสนอ.<br/>            อ่าน/เขียน [`IVbaProject`](/slides/python-net/th/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/presentation/hyperlink_queries/) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์การนำเสนอทั้งหมดอย่างง่าย (ไม่รวมในมาสเตอร์, เลเอาต์, สไลด์โน้ต).<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/th/aspose.slides/presentation/view_properties/) | รับคุณสมบัติมุมมองทั่วการนำเสนอ.<br/>            อ่านอย่างเดียว [`IViewProperties`](/slides/python-net/th/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/th/aspose.slides/presentation/first_slide_number/) | แสดงหมายเลขสไลด์แรกในการนำเสนอ |
| [`sensitivity_labels`](/slides/python-net/th/aspose.slides/presentation/sensitivity_labels/) | คืนคอลเลกชันของป้ายกำกับความละเอียดอ่อนที่ใช้กับเอกสารการนำเสนอ.<br/>            อ่านอย่างเดียว [`ISensitivityLabelCollection`](/slides/python-net/th/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/th/aspose.slides/presentation/source_format/) | คืนข้อมูลว่าการนำเสนอถูกโหลดจากรูปแบบใด.<br/>            อ่านอย่างเดียว [`SourceFormat`](/slides/python-net/th/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/th/aspose.slides/presentation/master_theme/) | คืนค่า master theme.<br/>            อ่านอย่างเดียว [`IMasterTheme`](/slides/python-net/th/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/th/aspose.slides/presentation/presentation/) |  |

## เมธอด

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงไฟล์ในรูปแบบที่ระบุ. |
| [`save(self, stream, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงสตรีมในรูปแบบที่ระบุ. |
| [`save(self, fname, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอลงสตรีมในรูปแบบที่ระบุพร้อมตัวเลือกเพิ่มเติม. |
| [`save(self, options)`](/slides/python-net/th/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | บันทึกสไลด์ทั้งหมดของการนำเสนอเป็นชุดไฟล์ที่เป็นเครื่องหมาย XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ในรูปแบบที่ระบุ พร้อมคงหมายเลขหน้า. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอลงไฟล์ในรูปแบบที่ระบุ พร้อมคงหมายเลขหน้า. |
| [`save(self, stream, slides, format)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของการนำเสนอลงสตรีมในรูปแบบที่ระบุ พร้อมคงหมายเลขหน้า. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/th/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของการนำเสนอลงสตรีมในรูปแบบที่ระบุ พร้อมคงหมายเลขหน้า. |
| [`get_images(self, options)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | คืนอ็อบเจกต์ Image สำหรับสไลด์ทั้งหมดของการนำเสนอ. |
| [`get_images(self, options, slides)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอ. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอพร้อมการปรับสเกลแบบกำหนดเอง. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอพร้อมการปรับสเกลแบบกำหนดเอง. |
| [`get_images(self, options, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของการนำเสนอด้วยขนาดที่ระบุ. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/th/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | คืนอ็อบเจกต์ Thumbnail Image สำหรับสไลด์ที่ระบุของการนำเสนอด้วยขนาดที่ระบุ. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | เน้นข้อความที่ตรงทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | เน้นข้อความที่ตรงทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`get_slide_by_id(self, id)`](/slides/python-net/th/aspose.slides/presentation/get_slide_by_id/#int) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/presentation/join_portions_with_same_formatting/#) | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ในสไลด์ทั้งหมด. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | เน้นผลลัพธ์ที่ตรงกับ regular expression ทั้งหมดด้วยสีที่ระบุ. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่ทุกการปรากฏของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/presentation/replace_regex/#str-str) | แทนที่ผลลัพธ์ที่ตรงกับ regular expression ทั้งหมดด้วยสตริงที่ระบุ. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/th/aspose.slides/presentation/refresh_charts_data/#bool) | โหลดข้อมูลของแผนภูมิทั้งหมดในการนำเสนอใหม่จากไฟล์ workbook ต้นทาง. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)