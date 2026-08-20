---
title: WarningType
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: แสดงประเภทของคำเตือน.
type: docs
url: /th/com.aspose.slides/warningtype/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

แสดงประเภทของคำเตือน.
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | พบปัญหาในเอกสารต้นฉบับ ทำให้เป็นไปได้สูงว่าเอกสารจะไม่สามารถเปิดได้หากบันทึกในรูปแบบเดิม |
| [DataLoss](#DataLoss) | ข้อความ/แผนภูมิ/รูปภาพ หรือข้อมูลอื่นจะหายสิ้นจากโครงสร้างเอกสารหลังจากโหลด หรือจากเอกสารที่สร้างขึ้นหลังจากบันทึก |
| [MajorFormattingLoss](#MajorFormattingLoss) | การสูญเสียการจัดรูปแบบอย่างมาก |
| [MinorFormattingLoss](#MinorFormattingLoss) | การสูญเสียการจัดรูปแบบเล็กน้อย |
| [CompatibilityIssue](#CompatibilityIssue) | นี่เป็นปัญหาที่ทราบกันว่าจะทำให้เอกสารไม่สามารถเปิดได้โดยเอเย่นต์ผู้ใช้บางตัว หรือเวอร์ชันก่อนของเอเย่นต์ผู้ใช้ |
| [UnexpectedContent](#UnexpectedContent) | เนื้อหาบางส่วนในเอกสารต้นทางไม่สามารถรับรู้ได้ (เช่น ไม่รองรับ) ซึ่งอาจทำให้เกิดปัญหาหรือไม่ก็อาจทำให้ข้อมูล/การจัดรูปแบบสูญหาย |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


พบปัญหาในเอกสารต้นฉบับ ทำให้เป็นไปได้สูงว่าเอกสารจะไม่สามารถเปิดได้หากบันทึกในรูปแบบเดิม

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


ข้อความ/แผนภูมิ/รูปภาพ หรือข้อมูลอื่นจะหายสิ้นจากโครงสร้างเอกสารหลังจากโหลด หรือจากเอกสารที่สร้างขึ้นหลังจากบันทึก

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```


การสูญเสียการจัดรูปแบบอย่างมาก

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```


การสูญเสียการจัดรูปแบบเล็กน้อย

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```


นี่เป็นปัญหาที่ทราบกันว่าจะทำให้เอกสารไม่สามารถเปิดได้โดยเอเย่นต์ผู้ใช้บางตัว หรือเวอร์ชันก่อนของเอเย่นต์ผู้ใช้

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


เนื้อหาบางส่วนในเอกสารต้นทางไม่สามารถรับรู้ได้ (เช่น ไม่รองรับ) ซึ่งอาจทำให้เกิดปัญหาหรือไม่ก็อาจทำให้ข้อมูล/การจัดรูปแบบสูญหาย