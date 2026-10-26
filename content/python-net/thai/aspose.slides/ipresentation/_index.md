---
title: IPresentation class
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/ipresentation/
---
## คลาส IPresentation

เอกสาร Presentation

ประเภท IPresentation เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`current_date_time`](/slides/python-net/th/aspose.slides/ipresentation/current_date_time/) | คืนค่า หรือกำหนดวันที่และเวลา ซึ่งจะใช้แทนเนื้อหาของฟิลด์วันที่และเวลา.<br/>            เวลาในการสร้างอ็อบเจ็กต์ Presentation นี้โดยค่าเริ่มต้น.<br/>            อ่าน/เขียน **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/th/aspose.slides/ipresentation/header_footer_manager/) | คืนค่า HeaderFooter manager ของงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IPresentationHeaderFooterManager`](/slides/python-net/th/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/th/aspose.slides/ipresentation/protection_manager/) | รับ manager ของสิทธิ์สำหรับงานนำเสนอนี้.<br/>            อ่านอย่างเดียว [`IProtectionManager`](/slides/python-net/th/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/th/aspose.slides/ipresentation/slides/) | คืนค่ารายการสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ.<br/th/>            อ่านอย่างเดียว [`ISlideCollection`](/slides/python-net/th/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/th/aspose.slides/ipresentation/sections/) | คืนค่ารายการส่วนของสไลด์ทั้งหมดที่กำหนดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`ISectionCollection`](/slides/python-net/th/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/th/aspose.slides/ipresentation/slide_size/) | คืนค่าอ็อบเจ็กต์ขนาดสไลด์.<br/>            อ่านอย่างเดียว [`ISlideSize`](/slides/python-net/th/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/th/aspose.slides/ipresentation/notes_size/) | คืนค่าอ็อบเจ็กต์ขนาดสไลด์โน้ต.<br/>            อ่านอย่างเดียว [`INotesSize`](/slides/python-net/th/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/th/aspose.slides/ipresentation/layout_slides/) | คืนค่ารายการสไลด์เลย์เอาต์ทั้งหมดที่กำหนดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IGlobalLayoutSlideCollection`](/slides/python-net/th/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/th/aspose.slides/ipresentation/masters/) | คืนค่ารายการมาสเตอร์สไลด์ทั้งหมดที่กำหนดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IMasterSlideCollection`](/slides/python-net/th/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/th/aspose.slides/ipresentation/master_notes_slide_manager/) | คืนค่า notes master manager.<br/>            อ่านอย่างเดียว [`IMasterNotesSlideManager`](/slides/python-net/th/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/th/aspose.slides/ipresentation/master_handout_slide_manager/) | คืนค่า handout master manager.<br/>            อ่านอย่างเดียว [`IMasterHandoutSlideManager`](/slides/python-net/th/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/th/aspose.slides/ipresentation/fonts_manager/) | คืนค่า fonts manager.<br/>            อ่านอย่างเดียว [`IFontsManager`](/slides/python-net/th/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/th/aspose.slides/ipresentation/default_text_style/) | คืนค่าสไตล์ข้อความเริ่มต้นสำหรับ shapes.<br/>            อ่านอย่างเดียว [`ITextStyle`](/slides/python-net/th/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/th/aspose.slides/ipresentation/comment_authors/) | คืนค่าคอลเลกชันของผู้เขียนคอมเมนต์.<br/>            อ่านอย่างเดียว [`ICommentAuthorCollection`](/slides/python-net/th/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/th/aspose.slides/ipresentation/document_properties/) | คืนค่าอ็อบเจ็กต์ DocumentProperties ที่มีคุณสมบัติเ�เอกสารมาตรฐานและกำหนดเอง.<br/>            อ่านอย่างเดียว [`IDocumentProperties`](/slides/python-net/th/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/th/aspose.slides/ipresentation/images/) | คืนค่าคอลเลกชันของรูปภาพทั้งหมดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IImageCollection`](/slides/python-net/th/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/th/aspose.slides/ipresentation/audios/) | คืนค่าคอลเลกชันของไฟล์เสียงฝังทั้งหมดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IAudioCollection`](/slides/python-net/th/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/th/aspose.slides/ipresentation/videos/) | คืนค่าคอลเลกชันของไฟล์วิดีโอฝังทั้งหมดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IVideoCollection`](/slides/python-net/th/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/th/aspose.slides/ipresentation/custom_data/) | คืนค่าข้อมูลกำหนดเองของงานนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomData`](/slides/python-net/th/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/th/aspose.slides/ipresentation/vba_project/) | รับโครงการ VBA ที่มีมาโครของงานนำเสนอ.<br/>            อ่าน/เขียน [`IVbaProject`](/slides/python-net/th/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/th/aspose.slides/ipresentation/source_format/) | คืนข้อมูลเกี่ยวกับรูปแบบที่งานนำเสนอถูกโหลด.<br/>            อ่านอย่างเดียว [`IPresentation.source_format`](/slides/python-net/th/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/th/aspose.slides/ipresentation/master_theme/) | คืนค่า theme มาสเตอร์ของงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IMasterTheme`](/slides/python-net/th/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/th/aspose.slides/ipresentation/hyperlink_queries/) | ให้การเข้าถึงลิงก์ทั้งหมดที่อยู่ในสไลด์งานนำเสนอ (ไม่รวมมาสเตอร์, เลย์เอาต์, สไลด์โน้ต).<br/>            อ่านอย่างเดียว [`IHyperlinkQueries`](/slides/python-net/th/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/th/aspose.slides/ipresentation/view_properties/) | รับคุณสมบัติการมองเห็นระดับงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IViewProperties`](/slides/python-net/th/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/th/aspose.slides/ipresentation/first_slide_number/) | แทนค่าหมายเลขสไลด์แรกในงานนำเสนอ.<br/>            อ่าน/เขียน **int**. |
| [`all_custom_xml_parts`](/slides/python-net/th/aspose.slides/ipresentation/all_custom_xml_parts/) | คืนส่วนข้อมูลกำหนดเองทั้งหมดในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`ICustomXmlPart`](/slides/python-net/th/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/th/aspose.slides/ipresentation/digital_signatures/) | คืนค่าคอลเลกชันของลายเซ็นที่ใช้ลงนในงานนำเสนอ.<br/>            อ่านอย่างเดียว [`IDigitalSignatureCollection`](/slides/python-net/th/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/th/aspose.slides/ipresentation/sensitivity_labels/) | คืนค่าคอลเลกชันของป้ายความอ่อนไหวที่ใส่ในเอกสารงานนำเสนอ.<br/>            อ่านอย่างเดียว [`ISensitivityLabelCollection`](/slides/python-net/th/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/th/aspose.slides/ipresentation/presentation/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/th/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [`save(self, stream, format)`](/slides/python-net/th/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมด้วยรูปแบบที่ระบุ. |
| [`save(self, fname, format, options)`](/slides/python-net/th/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม. |
| [`save(self, stream, format, options)`](/slides/python-net/th/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอลงสตรีมด้วยรูปแบบที่ระบุและตัวเลือกเพิ่มเติม. |
| [`save(self, fname, slides, format)`](/slides/python-net/th/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/th/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงไฟล์ด้วยรูปแบบที่ระบุ. |
| [`save(self, stream, slides, format)`](/slides/python-net/th/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมด้วยรูปแบบที่ระบุ. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/th/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | บันทึกสไลด์ที่ระบุของงานนำเสนอลงสตรีมด้วยรูปแบบที่ระบุ. |
| [`save(self, options)`](/slides/python-net/th/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | บันทึกสไลด์ทั้งหมดของงานนำเสนอเป็นชุดไฟล์ที่แสดง XAML markup. |
| [`get_images(self, options)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอ. |
| [`get_images(self, options, slides)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | คืนค่าอ็อบเจ็กต์ Thumbnail Bitmap สำหรับสไลด์ที่ระบุของงานนำเสนอ. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยการสเกลที่กำหนดเอง. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยการสเกลที่กำหนดเอง. |
| [`get_images(self, options, image_size)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ทั้งหมดของงานนำเสนอด้วยขนาดที่ระบุ. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/th/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | คืนค่าอ็อบเจ็กต์ Thumbnail Image สำหรับสไลด์ที่ระบุของงานนำเสนอด้วยขนาดที่ระบุ. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/th/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | ไฮไลต์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/th/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | ไฮไลต์การจับคู่ทั้งหมดของข้อความตัวอย่างด้วยสีที่ระบุ. |
| [`get_slide_by_id(self, id)`](/slides/python-net/th/aspose.slides/ipresentation/get_slide_by_id/#int) | คืนค่า Slide, MasterSlide หรือ LayoutSlide ตาม Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/th/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | รวม runs ที่มีรูปแบบเดียวกันในทุกย่อหน้าในทุก shape ที่ยอมรับในทุกสไลด์. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/th/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | ไฮไลต์การจับคู่ทั้งหมดของ regular expression ด้วยสีที่ระบุ. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/th/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | แทนที่การปรากฏทั้งหมดของข้อความที่ระบุด้วยข้อความอื่นที่ระบุ. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/th/aspose.slides/ipresentation/replace_regex/#str-str) | แทนที่การจับคู่ทั้งหมดของ regular expression ด้วยสตริงที่ระบุ. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)