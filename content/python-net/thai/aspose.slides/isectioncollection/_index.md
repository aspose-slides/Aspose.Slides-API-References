---
title: ISectionCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/isectioncollection/
---
## ISectionCollection คลาส

เป็นตัวแทนของคอลเลกชันของ sections.

ชนิด ISectionCollection เปิดเผยสมาชิกต่อไปนี้:

รับอิลเมนต์ที่ตำแหน่งที่ระบุ.
            อ่านอย่างเดียว [`ISection`](/slides/python-net/th/aspose.slides/isection).

## ดัชนี

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/isectioncollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/th/aspose.slides/isectioncollection/add_section/#str-islide) | เพิ่ม section ใหม่ที่เริ่มจาก slide เฉพาะ. |
| [`add_empty_section(self, name, index)`](/slides/python-net/th/aspose.slides/isectioncollection/add_empty_section/#str-int) | เพิ่ม section ว่างไปยังตำแหน่งที่ระบุของคอลเลกชัน. |
| [`remove_section_with_slides(self, section)`](/slides/python-net/th/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | ลบ section และสไลด์ที่อยู่ใน section. |
| [`remove_section(self, section)`](/slides/python-net/th/aspose.slides/isectioncollection/remove_section/#isection) | ลบ section. สไลด์ที่อยู่ใน section จะถูกรวมเข้ากับ section ก่อนหน้า. |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/th/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | ย้าย section และสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ. |
| [`append_empty_section(self, name)`](/slides/python-net/th/aspose.slides/isectioncollection/append_empty_section/#str) | เพิ่ม section ว่างไปยังส่วนท้ายของคอลเลกชัน. |
| [`index_of(self, section)`](/slides/python-net/th/aspose.slides/isectioncollection/index_of/#isection) | คืนค่าดัชนีของ section ที่ระบุในคอลเลกชัน. |
| [`clear(self)`](/slides/python-net/th/aspose.slides/isectioncollection/clear/#) | ลบ section ทั้งหมดออกจากคอลเลกชัน. |

### ดูเพิ่มเติม
* คลาส [`ISection`](/slides/python-net/th/aspose.slides/isection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)