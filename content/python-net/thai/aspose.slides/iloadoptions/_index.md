---
title: ILoadOptions class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iloadoptions/
---
## ILoadOptions คลาส

อนุญาตให้ระบุตัวเลือกเพิ่มเติม (เช่น รูปแบบหรือฟอนต์เริ่มต้น) เมื่อโหลดการนำเสนอ

ประเภท ILoadOptions เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| คุณสมบัติ | คำอธิบาย |
| :- | :- |
| [`load_format`](/slides/python-net/th/aspose.slides/iloadoptions/load_format/) | คืนค่า หรือกำหนดรูปแบบของการนำเสนอที่จะโหลด.<br/>            อ่าน/เขียน [`LoadFormat`](/slides/python-net/th/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/th/aspose.slides/iloadoptions/default_regular_font/) | คืนค่า หรือกำหนดฟอนต์ Regular ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ.<br/>            อ่าน-เขียน **str**. |
| [`default_symbol_font`](/slides/python-net/th/aspose.slides/iloadoptions/default_symbol_font/) | คืนค่า หรือกำหนดฟอนต์ Symbol ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ.<br/>            อ่าน-เขียน **str**. |
| [`default_asian_font`](/slides/python-net/th/aspose.slides/iloadoptions/default_asian_font/) | คืนค่า หรือกำหนดฟอนต์ Asian ที่ใช้ในกรณีที่ไม่พบฟอนต์ต้นฉบับ.<br/>            อ่าน-เขียน **str**. |
| [`password`](/slides/python-net/th/aspose.slides/iloadoptions/password/) | รับหรือกำหนดรหัสผ่าน.<br/>            อ่าน-เขียน **str**. |
| [`only_load_document_properties`](/slides/python-net/th/aspose.slides/iloadoptions/only_load_document_properties/) | คุณสมบัตินี้มีความหมายหากไฟล์การนำเสนอถูกป้องกันด้วยรหัสผ่าน.<br/>            ค่า true หมายความว่าต้องโหลดเฉพาะคุณสมบัติเอกสารจากไฟล์การนำเสนอที่เข้ารหัสและต้องละเว้นรหัสผ่าน.<br/>            ค่า false หมายความว่าต้องโหลดการนำเสนอที่เข้ารหัสทั้งหมดโดยใช้รหัสผ่านที่ถูกต้อง.<br/>            หากการนำเสนอไม่ได้เข้ารหัสค่าของคุณสมบัติก็จะถูกละเว้นเสมอ.<br/>            หากคุณสมบัติเอกสารของไฟล์ที่เข้ารหัสไม่ได้เป็นสาธารณะและค่าของคุณสมบัติเป็น true แล้ว<br/>            คุณสมบัติเอกสารไม่สามารถโหลดได้และจะเกิดข้อยกเว้น.<br/>            อ่าน-เขียน **bool**. |
| [`warning_callback`](/slides/python-net/th/aspose.slides/iloadoptions/warning_callback/) | คืนค่า หรือกำหนดออบเจ็กต์ที่รับคำเตือนและตัดสินใจว่ากระบวนการโหลดจะดำเนินต่อหรือยกเลิก.<br/>            อ่าน/เขียน [`IWarningCallback`](/slides/python-net/th/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/th/aspose.slides/iloadoptions/blob_management_options/) | แสดงตัวเลือกที่ใช้จัดการพฤติกรรมการจัดการ Binary Large Objects (BLOBs),<br/>            เช่น การใช้ไฟล์ชั่วคราวหรือจำนวนไบต์สูงสุดของ BLOBs ในหน่วยความจำ ตัวเลือกเหล่านี้มุ่งมั่นตั้งค่าอัตราส่วนประสิทธิภาพ/การใช้หน่วยความจำที่ดีที่สุดสำหรับสภาพแวดล้อมหรือความต้องการเฉพาะ.<br/>            Binary Large Object (BLOB) คือข้อมูลไบนารีที่เก็บเป็นเอนทิตีเดียว – ตัวอย่างเช่น BLOB สามารถเป็นไฟล์เสียง, วิดีโอ หรือการนำเสนอเอง. |
| [`document_level_font_sources`](/slides/python-net/th/aspose.slides/iloadoptions/document_level_font_sources/) | ระบุแหล่งที่มาของฟอนต์ภายนอกที่การนำเสนอจะใช้.<br/>            ฟอนต์เหล่านี้จะพร้อมใช้ตลอดอายุการใช้งานของการนำเสนอและจะไม่แชร์กับการนำเสนออื่น. |
| [`interruption_token`](/slides/python-net/th/aspose.slides/iloadoptions/interruption_token/) | โทเค็นสำหรับตรวจสอบคำขอการหยุดทำงาน.<br/>            <br/>            โทเค็นนี้จัดการอายุการใช้งานของอินสแตนซ์ [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) ทั้งหมด. การดำเนินการที่ใช้เวลานานใด ๆ เช่น การโหลดหรือการบันทึกการนำเสนอ จะถูกหยุดโดยการเรียกเมธอด [`IInterruptionTokenSource.interrupt`](/slides/python-net/th/aspose.slides/iinterruptiontokensource/interrupt) ของ [`IInterruptionTokenSource`](/slides/python-net/th/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/th/aspose.slides/iloadoptions/resource_loading_callback/) | คืนค่า หรือกำหนดอินเตอร์เฟซ callback ที่จัดการการโหลดทรัพยากรภายนอก.<br/>            อ่าน/เขียน [`IResourceLoadingCallback`](/slides/python-net/th/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/th/aspose.slides/iloadoptions/spreadsheet_options/) | แสดงตัวเลือกที่ใช้ระบุพฤติกรรมสเปรดชีตเพิ่มเติม. |
| [`default_text_language`](/slides/python-net/th/aspose.slides/iloadoptions/default_text_language/) | คืนค่า หรือกำหนดภาษาดีฟอลต์สำหรับข้อความในการนำเสนอ.<br/>             อ่าน-เขียน **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/th/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | กำหนดว่า Aspose.Slides จะลบออบเจ็กต์ไบนารีที่ฝังทั้งหมดขณะโหลดการนำเสนอหรือไม่.<br/>            <br/>ประเภทของออบเจ็กต์ไบนารีที่ฝัง:<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/th/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/th/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/th/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            อ่าน-เขียน **bool**. |


### ดูเพิ่มเติม
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)