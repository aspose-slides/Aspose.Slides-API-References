---
title: PdfAccessPermissions
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: ประกอบด้วยชุดของแฟล็กที่ระบุว่าควรให้สิทธิการเข้าถึงใดบ้างเมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้
type: docs
url: /th/com.aspose.slides/pdfaccesspermissions/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

ประกอบด้วยชุดของแฟล็กที่ระบุว่าควรให้สิทธิการเข้าถึงใดบ้างเมื่อเอกสารถูกเปิดด้วยสิทธิของผู้ใช้
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [None](#None) | ระบุว่าผู้ใช้ไม่มีสิทธิการเข้าถึง |
| [PrintDocument](#PrintDocument) | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่ใช่ระดับคุณภาพสูงสุด ขึ้นอยู่กับว่าบิต [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ถูกตั้งค่าอยู่หรือไม่) |
| [ModifyContent](#ModifyContent) | ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาในเอกสารได้โดยการทำงานที่ไม่ใช่บิตที่ควบคุมโดย [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) หรือไม่ |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | ระบุว่าผู้ใช้สามารถคัดลอกหรือสกัดข้อความและกราฟิกจากเอกสารโดยการทำงานที่ไม่ใช่บิต [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) หรือไม่ |
| [AddOrModifyFields](#AddOrModifyFields) | ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, เติมฟอร์มโต้ตอบ, และหากบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ถูกตั้งค่าอยู่ด้วย, สามารถสร้างหรือแก้ไขฟอร์มโต้ตอบ (รวมถึงฟิลด์ลายเซ็น) หรือไม่ |
| [FillExistingFields](#FillExistingFields) | ระบุว่าผู้ใช้สามารถเติมฟิลด์ฟอร์มโต้ตอบที่มีอยู่แล้ว (รวมถึงฟิลด์ลายเซ็น) ได้หรือไม่ แม้ว่าบิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) จะไม่ได้ตั้งค่า |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | ระบุว่าผู้ใช้สามารถสกัดข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงของผู้ใช้ที่มีความพิการหรือเพื่อการใช้งานอื่นได้หรือไม่ |
| [AssembleDocument](#AssembleDocument) | ระบุว่าผู้ใช้สามารถประกอบเอกสาร (แทรก, หมุน, หรือ ลบหน้าและสร้างบุ๊กมาร์กหรือภาพย่อ) ได้หรือไม่ แม้ว่าบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) จะไม่ได้ตั้งค่า |
| [HighQualityPrint](#HighQualityPrint) | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นรูปแบบที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของเนื้อหา PDF ได้หรือไม่ |
### ไม่มี {#None}
```
public static final int None
```

ระบุว่าผู้ใช้ไม่มีสิทธิการเข้าถึง

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่ใช่ระดับคุณภาพสูงสุด ขึ้นอยู่กับว่าบิต [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ถูกตั้งค่าอยู่หรือไม่)

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาในเอกสารได้โดยการทำงานที่ไม่ใช่บิตที่ควบคุมโดย [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) หรือไม่

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

ระบุว่าผู้ใช้สามารถคัดลอกหรือสกัดข้อความและกราฟิกจากเอกสารโดยการทำงานที่ไม่ใช่บิต [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) หรือไม่

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, เติมฟอร์มโต้ตอบ, และหากบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ถูกตั้งค่าอยู่ด้วย, สามารถสร้างหรือแก้ไขฟอร์มโต้ตอบ (รวมถึงฟิลด์ลายเซ็น) หรือไม่

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

ระบุว่าผู้ใช้สามารถเติมฟิลด์ฟอร์มโต้ตอบที่มีอยู่แล้ว (รวมถึงฟิลด์ลายเซ็น) ได้หรือไม่ แม้ว่าบิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) จะไม่ได้ตั้งค่า

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

ระบุว่าผู้ใช้สามารถสกัดข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงของผู้ใช้ที่มีความพิการหรือเพื่อการใช้งานอื่นได้หรือไม่

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

ระบุว่าผู้ใช้สามารถประกอบเอกสาร (แทรก, หมุน, หรือ ลบหน้าและสร้างบุ๊กมาร์กหรือภาพย่อ) ได้หรือไม่ แม้ว่าบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) จะไม่ได้ตั้งค่า

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นรูปแบบที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของเนื้อหา PDF ได้หรือไม่ เมื่อบิตนี้ไม่ได้ตั้งค่า (และบิต [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) ถูกตั้งค่า) การพิมพ์จะถูกจำกัดให้เป็นการแสดงผลระดับต่ำที่อาจมีคุณภาพลดลง