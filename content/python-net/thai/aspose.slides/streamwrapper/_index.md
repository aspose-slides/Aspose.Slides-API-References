---
title: StreamWrapper class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/streamwrapper/
---
## StreamWrapper คลาส

Aspose.IO.Stream wrapper for COM interface.

The StreamWrapper type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/th/aspose.slides/streamwrapper/stream/) | รับสตรีม.<br/>            อ่านอย่างเดียว **io.RawIOBase**. |
| [`can_read`](/slides/python-net/th/aspose.slides/streamwrapper/can_read/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันรองรับการอ่านหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`can_seek`](/slides/python-net/th/aspose.slides/streamwrapper/can_seek/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันรองรับการเลื่อนตำแหน่งหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`can_write`](/slides/python-net/th/aspose.slides/streamwrapper/can_write/) | รับค่าที่บ่งชี้ว่าสตรีมปัจจุบันรองรับการเขียนหรือไม่.<br/>            อ่านอย่างเดียว **bool**. |
| [`length`](/slides/python-net/th/aspose.slides/streamwrapper/length/) | รับความยาวของสตรีมเป็นไบต์.<br/>            อ่านอย่างเดียว **int**. |
| [`position`](/slides/python-net/th/aspose.slides/streamwrapper/position/) | รับหรือกำหนดตำแหน่งภายในสตรีมปัจจุบัน.<br/>            อ่านอย่างเดียว **int**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/th/aspose.slides/streamwrapper/close/#) | ปิดสตรีมปัจจุบันและปล่อยทรัพยากรทั้งหมด. |
| [`flush(self)`](/slides/python-net/th/aspose.slides/streamwrapper/flush/#) | ล้างบัฟเฟอร์ทั้งหมดสำหรับสตรีมนี้และทำให้ข้อมูลที่บัฟเฟอร์ไว้ถูกเขียนลงอุปกรณ์ฐาน. |
| [`read(self, buffer, offset, count)`](/slides/python-net/th/aspose.slides/streamwrapper/read/#bytes-int-int) | อ่านลำดับของไบต์จากสตรีมปัจจุบันและเลื่อนตำแหน่งภายในสตรีมตามจำนวนไบต์ที่อ่าน. |
| [`read_byte(self)`](/slides/python-net/th/aspose.slides/streamwrapper/read_byte/#) | อ่านไบต์หนึ่งจากสตรีมและเลื่อนตำแหน่งภายในสตรีมหนึ่งไบต์, หรือคืนค่า -1 หากถึงจุดสิ้นสุดของสตรีม. |
| [`seek(self, offset, origin)`](/slides/python-net/th/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | กำหนดตำแหน่งภายในสตรีมปัจจุบัน |
| [`write(self, buffer, offset, count)`](/slides/python-net/th/aspose.slides/streamwrapper/write/#bytes-int-int) | เขียนลำดับของไบต์ไปยังสตรีมปัจจุบันและเลื่อนตำแหน่งปัจจุบันภายในสตรีมนี้ตามจำนวนไบต์ที่เขียน. |
| [`write_byte(self, value)`](/slides/python-net/th/aspose.slides/streamwrapper/write_byte/#int) | เขียนไบต์หนึ่งไปยังตำแหน่งปัจจุบันในสตรีมและเลื่อนตำแหน่งภายในสตรีมหนึ่งไบต์. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)