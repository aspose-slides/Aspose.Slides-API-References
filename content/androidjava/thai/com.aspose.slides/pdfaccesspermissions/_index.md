---
title: PdfAccessPermissions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: มีชุดของธงที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดบ้างเมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้
type: docs
url: /th/com.aspose.slides/pdfaccesspermissions/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

มีชุดของธงที่ระบุว่าควรให้สิทธิ์การเข้าถึงใดบ้างเมื่อเอกสารถูกเปิดด้วยการเข้าถึงของผู้ใช้
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [None](#None) | ระบุว่าผู้ใช้ไม่มีสิทธิ์การเข้าถึง |
| [PrintDocument](#PrintDocument) | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่อยู่ในระดับคุณภาพสูงสุด ขึ้นอยู่กับว่าบิต [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ถูกตั้งค่าเช่นกันหรือไม่) |
| [ModifyContent](#ModifyContent) | ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาเอกสารโดยการดำเนินการอื่นที่ไม่ถูกควบคุมโดยบิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) หรือไม่ |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | ระบุว่าผู้ใช้สามารถคัดลอกหรือสกัดข้อความและกราฟิกจากเอกสารโดยการดำเนินการอื่นที่ไม่ถูกควบคุมโดยบิต [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) หรือไม่ |
| [AddOrModifyFields](#AddOrModifyFields) | ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, กรอกฟิลด์ฟอร์มโต้ตอบ, และหากบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ถูกตั้งค่าเช่นกัน สามารถสร้างหรือแก้ไขฟิลด์ฟอร์มโต้ตอบ (รวมถึงฟิลด์ลายมือชื่อ) หรือไม่ |
| [FillExistingFields](#FillExistingFields) | ระบุว่าผู้ใช้สามารถกรอกฟิลด์ฟอร์มโต้ตอบที่มีอยู่ (รวมถึงฟิลด์ลายมือชื่อ) แม้บิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) จะไม่ตั้งค่า |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | ระบุว่าผู้ใช้สามารถสกัดข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงสำหรับผู้ใช้ที่มีความพิการหรือเพื่อวัตถุประสงค์อื่นหรือไม่ |
| [AssembleDocument](#AssembleDocument) | ระบุว่าผู้ใช้สามารถประกอบเอกสาร (แทรก, หมุน, หรือลบหน้าและสร้างบุ๊คมาร์คหรือภาพย่อ) แม้บิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) จะไม่ตั้งค่า |
| [HighQualityPrint](#HighQualityPrint) | ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นรูปแบบที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของเนื้อหา PDF ได้หรือไม่ |

### None {#None}
```
public static final int None
```

ระบุว่าผู้ใช้ไม่มีสิทธิ์การเข้าถึง

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

ระบุว่าผู้ใช้สามารถพิมพ์เอกสารได้หรือไม่ (อาจไม่อยู่ในระดับคุณภาพสูงสุด ขึ้นอยู่กับว่าบิต [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ถูกตั้งค่าเช่นกันหรือไม่)

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

ระบุว่าผู้ใช้สามารถแก้ไขเนื้อหาเอกสารโดยการดำเนินการอื่นที่ไม่ถูกควบคุมโดยบิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) หรือไม่

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

ระบุว่าผู้ใช้สามารถคัดลอกหรือสกัดข้อความและกราฟิกจากเอกสารโดยการดำเนินการอื่นที่ไม่ถูกควบคุมโดยบิต [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) หรือไม่

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

ระบุว่าผู้ใช้สามารถเพิ่มหรือแก้ไขคำอธิบายข้อความ, กรอกฟิลด์ฟอร์มโต้ตอบ, และหากบิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ถูกตั้งค่าเช่นกัน สามารถสร้างหรือแก้ไขฟิลด์ฟอร์มโต้ตอบ (รวมถึงฟิลด์ลายมือชื่อ) หรือไม่

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

ระบุว่าผู้ใช้สามารถกรอกฟิลด์ฟอร์มโต้ตอบที่มีอยู่ (รวมถึงฟิลด์ลายมือชื่อ) แม้บิต [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) จะไม่ตั้งค่า

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

ระบุว่าผู้ใช้สามารถสกัดข้อความและกราฟิกเพื่อสนับสนุนการเข้าถึงสำหรับผู้ใช้ที่มีความพิการหรือเพื่อวัตถุประสงค์อื่นหรือไม่

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

ระบุว่าผู้ใช้สามารถประกอบเอกสาร (แทรก, หมุน, หรือลบหน้าและสร้างบุ๊คมาร์คหรือภาพย่อ) แม้บิต [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) จะไม่ตั้งค่า

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

ระบุว่าผู้ใช้สามารถพิมพ์เอกสารเป็นรูปแบบที่สามารถสร้างสำเนาดิจิทัลที่แม่นยำของเนื้อหา PDF ได้หรือไม่ เมื่อบิตนี้ไม่ตั้งค่า (และบิต [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) ถูกตั้งค่า) การพิมพ์จะถูกจำกัดให้อยู่ในรูปแบบระดับต่ำของการแสดงผล ซึ่งอาจมีคุณภาพลดลง