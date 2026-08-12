---
title: PdfAccessPermissions
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: มีชุดของแฟล็กที่ระบุว่าการอนุญาตการเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้
type: docs
weight: 989
url: /th/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum


ระบุชุดของแฟล็กที่กำหนดว่าการอนุญาตการเข้าถึงใดควรให้เมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้.

```cpp
enum class PdfAccessPermissions
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ระบุว่าผู้ใช้ไม่มีสิทธิ์การเข้าถึง |
| PrintDocument | 4 | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่ได้ระดับคุณภาพสูงสุด ขึ้นอยู่กับว่าบิต [PdfAccessPermissions::HighQualityPrint](./) ถูกตั้งค่าเพิ่มด้วยหรือไม่) |
| ModifyContent | 8 | ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาในเอกสารโดยการดำเนินการที่ไม่ได้ถูกควบคุมโดยบิต [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./) หรือไม่ |
| CopyTextAndGraphics | 16 | ระบุว่าผู้ใช้สามารถคัดลอกหรือดึงข้อความและกราฟิกจากเอกสารโดยการดำเนินการที่ไม่ได้ถูกควบคุมโดยบิต [PdfAccessPermissions::ExtractTextAndGraphics](./) หรือไม่ |
| AddOrModifyFields | 32 | ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, เติมฟิลด์ฟอร์มโต้ตอบ, และหากบิต [PdfAccessPermissions::ModifyContent](./) ถูกตั้งค่าเพิ่มด้วย, สร้างหรือแก้ไขฟิลด์ฟอร์มโต้ตอบ (รวมถึงฟิลด์ลายเซ็น) หรือไม่ |
| FillExistingFields | 256 | ระบุว่าผู้ใช้สามารถเติมฟิลด์ฟอร์มโต้ตอบที่มีอยู่ (รวมถึงฟิลด์ลายเซ็น) แม้ว่าบิต [PdfAccessPermissions::AddOrModifyFields](./) จะไม่ได้ตั้งค่า |
| ExtractTextAndGraphics | 512 | ระบุว่าผู้ใช้สามารถดึงข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงสำหรับผู้ใช้ที่มีความบกพร่องหรือเพื่อวัตถุประสงค์อื่นได้หรือไม่ |
| AssembleDocument | 1024 | ระบุว่าผู้ใช้สามารถประกอบเอกสาร (แทรก, หมุน, หรือลบหน้าและสร้างที่คั่นหน้า หรือภาพย่อ) แม้ว่าบิต [PdfAccessPermissions::ModifyContent](./) จะไม่ได้ตั้งค่า |
| HighQualityPrint | 2048 | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นรูปแบบที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของเนื้อหา PDF ได้หรือไม่ เมื่อบิตนี้ไม่ได้ตั้งค่า (และบิต [PdfAccessPermissions::PrintDocument](./) ถูกตั้งค่า) การพิมพ์จะถูกจำกัดไว้ที่การแสดงผลระดับต่ำ ซึ่งอาจมีคุณภาพต่ำลง |

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::Export](../)
* ไลบรารี [Aspose.Slides](../../)