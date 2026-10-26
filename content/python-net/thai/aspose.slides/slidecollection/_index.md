---
title: SlideCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/slidecollection/
---
## SlideCollection คลาส

แสดงถึงคอลเลกชันของสไลด์.

ประเภท SlideCollection เปิดเผยสมาชิกต่อไปนี้:

ดึงเอาองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ.
อ่านอย่างเดียว [`Slide`](/slides/python-net/th/aspose.slides/slide).

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/slidecollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/th/aspose.slides/slidecollection/add_clone/#islide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/th/aspose.slides/slidecollection/add_clone/#islide-isection) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของส่วนที่ระบุ. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/th/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | เพิ่มสำเนาของสไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/th/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | เพิ่มสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน.<br/>            เค้าโครงที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ <br/>            (เค้าโครงที่เหมาะสมคือเค้าโครงที่มี Type หรือ Name เดียวกับ <br/>            เค้าโครงของสไลด์ต้นฉบับ). หากไม่มีเค้าโครงที่เหมาะสม then<br/>            เค้าโครงของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout <br/>            เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout<br/>            เป็น false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/th/aspose.slides/slidecollection/insert_clone/#int-islide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/th/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/th/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน.<br/>            เค้าโครงที่เหมาะสมจะถูกเลือกโดยอัตโนมัติจาก master ที่ระบุ <br/>            (เค้าโครงที่เหมาะสมคือเค้าโครงที่มี Type หรือ Name เดียวกับ <br/>            เค้าโครงของสไลด์ต้นฉบับ). หากไม่มีเค้าโครงที่เหมาะสม then<br/>            เค้าโครงของสไลด์ต้นฉบับจะถูกคัดลอก (หาก allowCloneMissingLayout <br/>            เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout<br/>            เป็น false). |
| [`to_array(self)`](/slides/python-net/th/aspose.slides/slidecollection/to_array/#) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมด. |
| [`to_array(self, start_index, count)`](/slides/python-net/th/aspose.slides/slidecollection/to_array/#int-int) | สร้างและคืนค่าอาร์เรย์ที่มีสไลด์ทั้งหมดจากช่วงที่ระบุ.<br/>            ดัชนีของสไลด์แรกที่ต้องการเพิ่ม จำนวนสไลด์ที่ต้องการเพิ่ม. |
| [`reorder(self, index, slide)`](/slides/python-net/th/aspose.slides/slidecollection/reorder/#int-islide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [`reorder(self, index, slides)`](/slides/python-net/th/aspose.slides/slidecollection/reorder/#int-listislide) | ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.<br/>            สไลด์จะถูกวางเริ่มจากดัชนีตามลำดับที่ปรากฏในรายการ. |
| [`add_from_pdf(self, path)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_pdf/#str) | สร้างสไลด์จากเอกสาร PDF แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | สร้างสไลด์จากเอกสาร PDF แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชันโดยพิจารณาตัวเลือกการนำเข้า PDF. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | สร้างสไลด์จากเอกสาร PDF แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | สร้างสไลด์จากเอกสาร PDF แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_text)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_html/#str) | สร้างสไลด์จากข้อความ HTML แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`add_from_html(self, html_stream)`](/slides/python-net/th/aspose.slides/slidecollection/add_from_html/#iorawiobase) | สร้างสไลด์จากข้อความ HTML แล้วเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-str) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/th/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | สร้างสไลด์จากข้อความ HTML แล้วแทรกลงในคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [`add_empty_slide(self, layout)`](/slides/python-net/th/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | เพิ่มสไลด์ใหม่ที่ว่างเปล่าไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/th/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. |
| [`remove(self, value)`](/slides/python-net/th/aspose.slides/slidecollection/remove/#islide) | ลบการปรากฏครั้งแรกของออบเจ็กต์ที่ระบุจากคอลเลกชัน. |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/slidecollection/remove_at/#int) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุจากคอลเลกชัน. |
| [`index_of(self, slide)`](/slides/python-net/th/aspose.slides/slidecollection/index_of/#islide) | คืนค่าดัชนีของสไลด์ที่ระบุในคอลเลกชัน. |

### ดูเพิ่มเติม
* คลาส [`Slide`](/slides/python-net/th/aspose.slides/slide)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)