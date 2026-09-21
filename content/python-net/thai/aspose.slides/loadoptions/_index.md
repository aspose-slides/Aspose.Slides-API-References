---
title: LoadOptions class
second_title: อ้างอิง API Aspose.Slides สำหรับ Python ผ่าน .NET
description: 
type: docs
url: /th/aspose.slides/loadoptions/
---
## LoadOptions คลาส

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือแบบอักษรเริ่มต้น) เมื่อโหลดการพรีเซนเทชัน

ชนิด LoadOptions เปิดเผยสมาชิกต่อไปนี้:

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| :- | :- |
| [`__init__(self)`](/slides/python-net/th/aspose.slides/loadoptions/__init__/#) | สร้างตัวเลือกการโหลดเริ่มต้นใหม่ |
| [`__init__(self, load_format)`](/slides/python-net/th/aspose.slides/loadoptions/__init__/#loadformat) | สร้างตัวเลือกการโหลดใหม่ |

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`load_format`](/slides/python-net/th/aspose.slides/loadoptions/load_format/) | คืนค่า หรือ ตั้งค่ารูปแบบของการพรีเซนเทชันที่จะโหลด<br/>            อ่าน/เขียน [`LoadFormat`](/slides/python-net/th/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides/loadoptions/default_regular_font/) | คืนค่า หรือ ตั้งค่าแบบอักษร Regular ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง<br/>            อ่าน/เขียน **str**. |
| [`default_symbol_font`](/slides/python-net/th/aspose.slides/loadoptions/default_symbol_font/) | คืนค่า หรือ ตั้งค่าแบบอักษร Symbol ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง<br/>            อ่าน/เขียน **str**. |
| [`default_asian_font`](/slides/python-net/th/aspose.slides/loadoptions/default_asian_font/) | คืนค่า หรือ ตั้งค่าแบบอักษร Asian ที่ใช้ในกรณีที่ไม่พบแบบอักษรต้นทาง<br/>            อ่าน/เขียน **str**. |
| [`password`](/slides/python-net/th/aspose.slides/loadoptions/password/) | รับหรือกำหนดรหัสผ่าน<br/>            อ่าน/เขียน **str**. |
| [`only_load_document_properties`](/slides/python-net/th/aspose.slides/loadoptions/only_load_document_properties/) | คุณสมบัตินี้มีความหมาย หากไฟล์พรีเซนเทชันถูกป้องกันด้วยรหัสผ่าน<br/>            ค่า true หมายความว่าจะโหลดเฉพาะคุณสมบัติด큐เมนต์จากไฟล์พรีเซนเทชันที่เข้ารหัสและจะละเลยรหัสผ่าน<br/>            ค่า false หมายความว่าจะโหลดพรีเซนเทชันที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง<br/>            หากพรีเซนเทชันไม่ได้เข้ารหัส ค่าของคุณสมบัติก็จะถูกละเลยเสมอ<br/>            หากคุณสมบัติด큐เมนต์ของไฟล์ที่เข้ารหัสไม่เป็นสาธารณะและค่าของคุณสมบัติเป็น true จะไม่สามารถโหลดคุณสมบัติด큐เมนต์ได้และจะเกิดข้อยกเว้น<br/>            อ่าน/เขียน **bool**. |
| [`warning_callback`](/slides/python-net/th/aspose.slides/loadoptions/warning_callback/) | คืนค่า หรือ ตั้งค่าวัตถุที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลด <br/>            จะดำเนินต่อหรือจะถูกยกเลิก<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/th/aspose.slides/loadoptions/blob_management_options/) | แสดงตัวเลือกที่สามารถใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs) <br/>            เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้ตั้งใจเพื่อกำหนดอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ<br/>            Binary Large Object (BLOB) คือข้อมูลไบนารีที่จัดเก็บเป็นเอนทิตี้เดียว - เช่น BLOB สามารถเป็นไฟล์เสียง วีดีโอ หรือพรีเซนเทชันเอง |
| [`document_level_font_sources`](/slides/python-net/th/aspose.slides/loadoptions/document_level_font_sources/) | ระบุแหล่งที่มาของแบบอักษรภายนอกที่จะใช้ในพรีเซนเทชัน<br/>            แบบอักษรเหล่านี้จะพร้อมใช้งานสำหรับพรีเซนเทชันตลอดอายุการใช้งานและไม่ถูกแชร์กับพรีเซนเทชันอื่น |
| [`interruption_token`](/slides/python-net/th/aspose.slides/loadoptions/interruption_token/) | โทเคนเพื่อเฝ้าตรวจสอบคำขอการหยุดชั่วคราว<br/>            <br/>            โทเคนนี้จัดการอายุการใช้งานทั้งหมดของอินสแตนซ์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) ใด ๆ การดำเนินการที่ใช้เวลานาน เช่น การโหลด <br/>            หรือการบันทึกพรีเซนเทชัน จะถูกหยุดโดยการเรียกเมธอด [`InterruptionTokenSource.interrupt`](/slides/python-net/th/aspose.slides/interruptiontokensource/interrupt) ของ <br/>            [`InterruptionTokenSource`](/slides/python-net/th/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/th/aspose.slides/loadoptions/resource_loading_callback/) | คืนค่า หรือ ตั้งค่าอินเทอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก<br/>            อ่าน/เขียน [`IResourceLoadingCallback`](/slides/python-net/th/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/th/aspose.slides/loadoptions/spreadsheet_options/) | รับตัวเลือกสำหรับสเปรดชีต ตัวอย่างเช่น ตัวเลือกเหล่านี้มีผลต่อการคำนวณสูตรสำหรับแผนภูมิ |
| [`default_text_language`](/slides/python-net/th/aspose.slides/loadoptions/default_text_language/) | คืนค่า หรือ ตั้งค่าภาษาเริ่มต้นสำหรับข้อความพรีเซนเทชัน<br/>            อ่าน/เขียน **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/th/aspose.slides/loadoptions/delete_embedded_binary_objects/) | กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังอยู่ทั้งหมดระหว่างการโหลดพรีเซนเทชันหรือไม่<br/>            <br/>ประเภทของออบเจ็กต์ไบนารีที่ฝังอยู่:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/th/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/th/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            อ่าน/เขียน **bool**. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)