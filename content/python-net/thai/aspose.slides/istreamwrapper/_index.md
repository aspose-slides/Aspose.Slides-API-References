---
title: IStreamWrapper class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/istreamwrapper/
---
## IStreamWrapper คลาส

ตัวห่อ Aspose.IO.Stream สำหรับอินเทอร์เฟซ COM.

The IStreamWrapper type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/th/aspose.slides/istreamwrapper/stream/) | รับสตรีมหนึ่งรายการ.<br/>            อ่านอย่างเดียว **io.RawIOBase**. |
| [`can_read`](/slides/python-net/th/aspose.slides/istreamwrapper/can_read/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันสนับสนุนการอ่านหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`can_seek`](/slides/python-net/th/aspose.slides/istreamwrapper/can_seek/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันสนับสนุนการเลื่อนตำแหน่งหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`can_write`](/slides/python-net/th/aspose.slides/istreamwrapper/can_write/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันสนับสนุนการเขียนหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`length`](/slides/python-net/th/aspose.slides/istreamwrapper/length/) | รับความยาวเป็นไบต์ของสตรีม.<br/>            อ่านอย่างเดียว **int**. |
| [`position`](/slides/python-net/th/aspose.slides/istreamwrapper/position/) | รับตำแหน่งภายในสตรีมปัจจุบัน.<br/>            อ่านอย่างเดียว **int**. |

## วิธีการ

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/th/aspose.slides/istreamwrapper/close/#) | ปิดสตรีมปัจจุบันและปล่อยทรัพยากรใด ๆ. |
| [`flush(self)`](/slides/python-net/th/aspose.slides/istreamwrapper/flush/#) | ล้างบัฟเฟอร์ทั้งหมดสำหรับสตรีมนี้และทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนลงอุปกรณ์พื้นฐาน. |
| [`read(self, buffer, offset, count)`](/slides/python-net/th/aspose.slides/istreamwrapper/read/#bytes-int-int) | อ่านลำดับของไบต์จากสตรีมปัจจุบันและเลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่านได้. |
| [`read_byte(self)`](/slides/python-net/th/aspose.slides/istreamwrapper/read_byte/#) | อ่านไบต์หนึ่งจากสตรีมและเลื่อนตำแหน่งภายในสตรีมหนึ่งไบต์ หรือคืนค่า -1 หากอยู่ที่ท้ายสตรีม. |
| [`seek(self, offset, origin)`](/slides/python-net/th/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | ตั้งค่าตำแหน่งภายในสตรีมปัจจุบัน |
| [`write(self, buffer, offset, count)`](/slides/python-net/th/aspose.slides/istreamwrapper/write/#bytes-int-int) | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันและเลื่อนตำแหน่งปัจจุบันภายในสตรีมนี้ตามจำนวนไบต์ที่เขียน. |
| [`write_byte(self, value)`](/slides/python-net/th/aspose.slides/istreamwrapper/write_byte/#int) | เขียนไบต์หนึ่งไปยังตำแหน่งปัจจุบันในสตรีมและเลื่อนตำแหน่งภายในสตรีมหนึ่งไบต์. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)