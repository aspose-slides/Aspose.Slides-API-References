---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection คลาส

เป็นการแสดงถึงคอลเลกชันของสไลด์เลเอาต์ทั้งหมดของสไลด์มาสเตอร์ที่กำหนด  
สืบทอดจาก LayoutSlideCollection คลาสพร้อมด้วยเมธอดสำหรับการเพิ่ม/แทรก/ลบ/ทำสำเนา/จัดเรียงสไลด์เลเอาต์ในบริบทของคอลเลกชันแยกของสไลด์เลเอาต์ของมาสเตอร์

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/th/aspose.slides/layoutslidecollection)

ประเภท MasterLayoutSlideCollection เปิดเผยสมาชิกต่อไปนี้:

## Indexer

| ชื่อ | คำอธิบาย |
| :- | :- |
| [`[index]`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | คืนค่าเลเอาต์สไลด์แรกของประเภทที่ระบุ.<br/>            ชนิดของเลเอาต์สไลด์ที่จะค้นหา [`LayoutSlide`](/slides/python-net/th/aspose.slides/layoutslide) ที่มีประเภทที่ระบุหรือ None หากไม่พบเลเอาต์ |
| [`remove(self, value)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | ลบเลเอาต์ออกจากคอลเลกชัน |
| [`remove_unused(self)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/remove_unused/#) | ลบเลเอาต์สไลด์ที่ไม่ได้ใช้ (เลเอาต์สไลด์ที่ HasDependingSlides เป็น false) |
| [`add_clone(self, source_layout)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | เพิ่มสำเนาของเลเอาต์สไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | แทรกสำเนาของเลเอาต์สไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [`add(self, layout_type, layout_name)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | เพิ่มเลเอาต์สไลด์ใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | แทรกเลเอาต์สไลด์ใหม่ไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [`remove_at(self, index)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/remove_at/#int) | ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน |
| [`reorder(self, index, layout_slide)`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | ย้ายเลเอาต์สไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ |

### ดูเพิ่มเติม
* คลาส [`LayoutSlideCollection`](/slides/python-net/th/aspose.slides/layoutslidecollection)
* คลาส [`MasterLayoutSlideCollection`](/slides/python-net/th/aspose.slides/masterlayoutslidecollection)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)