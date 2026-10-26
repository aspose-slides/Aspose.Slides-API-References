---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager คลาส

เป็นตัวจัดการที่เก็บพฤติกรรมของส่วนท้ายสไลด์บันทึกหลัก, ตัวแทนเวลาวันที่, ตัวแทนหมายเลขหน้า และตัวแทนทั้งหมดของส่วนย่อย  
Child placeholders mean placeholders are contained on depending notes slides.  
Depending notes slides use and depend on master notes slide.

**Inheritance:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/th/aspose.slides/baseheaderfootermanager)

The MasterNotesSlideHeaderFooterManager type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | รับค่าแสดงว่ามีตัวแทนส่วนท้ายอยู่.<br/>            Read **bool**. |
| [`is_slide_number_visible`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | รับค่าแสดงว่ามีตัวแทนหมายเลขหน้ามีอยู่.<br/>            Read**bool**. |
| [`is_date_time_visible`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | รับค่าแสดงว่ามีตัวแทนวัน-เวลาอยู่.<br/>            Read**bool**. |
| [`is_header_visible`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | รับค่าแสดงว่ามีตัวแทนส่วนหัวอยู่.<br/>            Read **bool**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายสไลด์. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนวัน-เวลาในสไลด์. |
| [`set_footer_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | ตั้งค่าข้อความให้กับตัวแทนส่วนท้ายสไลด์. |
| [`set_date_time_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | ตั้งค่าข้อความให้กับตัวแทนวัน-เวลาในสไลด์. |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนส่วนหัวสไลด์. |
| [`set_header_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | ตั้งค่าข้อความให้กับตัวแทนส่วนหัวสไลด์. |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนส่วนหัวสไลด์บันทึกหลักและตัวแทนส่วนหัวย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | ตั้งค่าข้อความให้กับตัวแทนส่วนหัวสไลด์บันทึกหลักและตัวแทนส่วนหัวย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนส่วนท้ายสไลด์หลักและตัวแทนส่วนท้ายย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนหมายเลขหน้าสไลด์หลักและตัวแทนหมายเลขหน้าย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | เปลี่ยนการมองเห็นของตัวแทนวัน-เวลาในสไลด์หลักและตัวแทนวัน-เวลาในสไลด์ย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | ตั้งค่าข้อความให้กับตัวแทนส่วนท้ายสไลด์หลักและตัวแทนส่วนท้ายย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | ตั้งค่าข้อความให้กับตัวแทนวัน-เวลาในสไลด์หลักและตัวแทนวัน-เวลาในสไลด์ย่อยทั้งหมด.<br/>            หมายถึงตัวแทนส่วนย่อยจะอยู่ในสไลด์บันทึกที่ขึ้นอยู่.<br/>            สไลด์บันทึกที่ขึ้นอยู่ใช้และพึ่งพาสไลด์บันทึกหลัก. |

### ดูเพิ่มเติม
* คลาส [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/basehandoutnotesslideheaderfootermanager)
* คลาส [`BaseHeaderFooterManager`](/slides/python-net/th/aspose.slides/baseheaderfootermanager)
* คลาส [`BaseSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/baseslideheaderfootermanager)
* คลาส [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/th/aspose.slides/masternotesslideheaderfootermanager)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)