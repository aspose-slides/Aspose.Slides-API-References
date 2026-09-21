---
title: ILinkEmbedController class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController คลาส

อินเตอร์เฟซ callback ที่ใช้กำหนดวิธีการประมวลผลวัตถุระหว่างการบันทึก

ประเภท ILinkEmbedController เปิดเผยสมาชิกต่อไปนี้:

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/th/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | กำหนดตำแหน่งที่วัตถุควรถูกจัดเก็บ.<br/>            วิธีนี้จะถูกเรียกหนึ่งครั้งสำหรับแต่ละ id ของวัตถุ.<br/>            ไม่รับประกันว่าจะไม่มีวัตถุสองรายการที่มีข้อมูล, semanticName และ contentType เดียวกันแต่มี id ต่างกัน. |
| [`get_url(self, id, referrer)`](/slides/python-net/th/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | คืนค่า URL ไปยังวัตถุภายนอก.<br/>            วิธีนี้จะถูกเรียกเสมอหาก **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** คืนค่า [`LinkEmbedDecision.LINK`](/slides/python-net/th/aspose.slides.export/linkembeddecision/LINK) และอาจถูกเรียกหาก **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** คืนค่า [`LinkEmbedDecision.EMBED`](/slides/python-net/th/aspose.slides.export/linkembeddecision/EMBED) แต่การฝังไม่ได้ผล.<br/>            สามารถเรียกหลายครั้งสำหรับ id ของวัตถุเดียวกัน. |
| [`save_external(self, id, entity_data)`](/slides/python-net/th/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | บันทึกวัตถุภายนอก. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)