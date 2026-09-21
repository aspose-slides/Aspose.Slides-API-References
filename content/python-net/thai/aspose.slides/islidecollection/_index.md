---
title: ISlideCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/islidecollection/
---
## ISlideCollection คลาส

เป็นตัวแทนของคอลเลกชันของสไลด์

ประเภท ISlideCollection เปิดเผยสมาชิกต่อไปนี้:

รับเอาอิลีเมนต์ที่ตำแหน่งที่ระบุ

อ่านอย่างเดียว [`ISlide`](/slides/python-net/th/aspose.slides/islide).

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/islidecollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/th/aspose.slides/islidecollection/add_clone/#islide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/th/aspose.slides/islidecollection/add_clone/#islide-isection) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/th/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/th/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่กำหนดไปยังตำแหน่งสุดท้ายของคอลเลกชัน.<br/>            รูปแบบที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่กำหนด <br/>            (รูปแบบที่เหมาะสมคือรูปแบบที่มี Type หรือ Name เท่ากับ <br/>            ของรูปแบบของสไลด์ต้นฉบับ). หากไม่มีรูปแบบที่เหมาะสมแล้ว<br/>            รูปแบบของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout <br/>            เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout<br/>            เป็น false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/th/aspose.slides/islidecollection/insert_clone/#int-islide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/th/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/th/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | แทรกสำเนาของสไลด์ต้นฉบับที่กำหนดไปยังตำแหน่งที่ระบุของคอลเลกชัน.<br/>            รูปแบบที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่กำหนด <br/>            (รูปแบบที่เหมาะสมคือรูปแบบที่มี Type หรือ Name เท่ากับ <br/>            ของรูปแบบของสไลด์ต้นฉบับ). หากไม่มีรูปแบบที่เหมาะสมแล้ว<br/>            รูปแบบของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout <br/>            เป็น true) หรือจะโยน PptxEditException (หาก allowCloneMissingLayout<br/>            เป็น false). |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/islidecollection/to_array/#) | สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมดอยู่ในนั้น. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/islidecollection/to_array/#int-int) | สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุอยู่ในนั้น. |
| [`reorder(self, index, slide)`](/slides/python-net/th/aspose.slides/islidecollection/reorder/#int-islide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [`reorder(self, index, slides)`](/slides/python-net/th/aspose.slides/islidecollection/reorder/#int-listislide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.<br/>            สไลด์จะถูกจัดวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ. |
| [`add_from_pdf(self, path)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_pdf/#str) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชันโดยพิจารณาตัวเลือกการนำเข้า pdf. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | สร้างสไลด์จากเอกสาร PDF และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_text)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_html/#str) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_stream)`](/slides/python-net/th/aspose.slides/islidecollection/add_from_html/#iorawiobase) | สร้างสไลด์จากข้อความ HTML และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-str) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-str-bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | สร้างสไลด์จากข้อความ HTML และแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`add_empty_slide(self, layout)`](/slides/python-net/th/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | เพิ่มสไลด์เปล่าใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/th/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [`remove(self, value)`](/slides/python-net/th/aspose.slides/islidecollection/remove/#islide) | ลบรายการแรกที่พบของออบเจ็กต์เฉพาะจากคอลเลกชัน. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/islidecollection/remove_at/#int) | ลบอิลีเมนต์ที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [`index_of(self, slide)`](/slides/python-net/th/aspose.slides/islidecollection/index_of/#islide) | คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |


### ดูเพิ่มเติม
* คลาส [`ISlide`](/slides/python-net/th/aspose.slides/islide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)