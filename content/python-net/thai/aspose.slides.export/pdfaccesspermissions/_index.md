---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API อ้างอิง
description: 
type: docs
url: /th/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enumeration

ประกอบด้วยชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรถูกมอบให้เมื่อเปิดเอกสารด้วยการเข้าถึงของผู้ใช้

ประเภท PdfAccessPermissions เปิดเผยสมาชิกต่อไปนี้:

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| :- | :- |
| NONE | ระบุว่าผู้ใช้ไม่มีการอนุญาตการเข้าถึง |
| PRINT_DOCUMENT | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่ได้คุณภาพระดับสูงสุด ขึ้นอยู่กับ <br/>            ว่าบิต [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) ถูกตั้งค่าเช่นกันหรือไม่) |
| MODIFY_CONTENT | ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาของเอกสารโดยการทำงานที่ไม่ใช่ที่ควบคุมโดยบิต<br/>            [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) หรือไม่ |
| COPY_TEXT_AND_GRAPHICS | ระบุว่าผู้ใช้สามารถคัดลอกหรือดึงข้อความและกราฟิกจากเอกสารได้หรือไม่โดยการทำงาน <br/>            ที่ไม่ใช่ที่ควบคุมโดยบิต [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) |
| ADD_OR_MODIFY_FIELDS | ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, เติมฟิลด์แบบโต้ตอบ, และหากบิต<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) ถูกตั้งค่าเช่นกัน, สร้างหรือแก้ไขฟิลด์แบบโต้ตอบ (รวมถึงฟิลด์ลายเซ็น <br/>            ) |
| FILL_EXISTING_FIELDS | ระบุว่าผู้ใช้สามารถเติมฟิลด์แบบโต้ตอบที่มีอยู่ (รวมถึงฟิลด์ลายเซ็น) ได้หรือไม่ แม้ว่าบิต<br/>            [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) จะไม่ตั้งค่า |
| EXTRACT_TEXT_AND_GRAPHICS | ระบุว่าผู้ใช้สามารถดึงข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงสำหรับผู้ใช้ที่มีความพิการ<br/>            หรือเพื่อวัตถุประสงค์อื่นได้หรือไม่ |
| ASSEMBLE_DOCUMENT | ระบุว่าผู้ใช้สามารถจัดเรียงเอกสาร (แทรก, หมุน, หรือลบหน้าและสร้างบุ๊คมาร์คหรือ<br/>            รูปภาพย่อ) ได้หรือไม่ แม้ว่าบิต [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) จะไม่ตั้งค่า |
| HIGH_QUALITY_PRINT | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นตัวแทนที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของ<br/>            เนื้อหา PDF ได้หรือไม่ เมื่อบิตนี้ไม่ตั้งค่า (และบิต [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/th/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) ตั้งค่า),<br/>            การพิมพ์จะถูกจำกัดไว้ที่การแสดงผลระดับต่ำ ซึ่งอาจมีคุณภาพที่ลดลง |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.export`](/slides/python-net/th/aspose.slides.export)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)