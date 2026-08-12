---
title: CreateXmlDeclaration()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างโหนด XmlDeclaration ด้วยค่าที่ระบุ
type: docs
weight: 378
url: /th/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) method

สร้างโหนด [XmlDeclaration](../../xmldeclaration/) ด้วยค่าที่ระบุ

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | เวอร์ชันต้องเป็น "1.0". |
| encoding | const [String](../../../system/string/)\& | ค่าของแอตทริบิวต์ encoding. นี่คือการเข้ารหัสที่ใช้เมื่อคุณบันทึก [XmlDocument](../) ลงไฟล์หรือสตรีม; ดังนั้นจึงต้องตั้งค่าเป็นสตริงที่รองรับโดยคลาส [Text::Encoding](../../../system.text/encoding/), มิฉะนั้นคำสั่ง "XmlDocument::Save(String)" จะล้มเหลว. หากค่านี้เป็น **nullptr** หรือ [String::Empty](../../../system/string/empty/), เมธอด [XmlDocument::Save](../save/) จะไม่เขียนแอตทริบิวต์ encoding ในประกาศ XML และดังนั้นจะใช้การเข้ารหัสเริ่มต้น UTF-8. |
| standalone | const [String](../../../system/string/)\& | ค่าต้องเป็น "yes" หรือ "no". หากเป็น **nullptr** หรือ [String::Empty](../../../system/string/empty/), เมธอด [XmlDocument::Save](../save/) จะไม่เขียนแอตทริบิวต์ standalone ในประกาศ XML. |

### Return Value

โหนด [XmlDeclaration](../../xmldeclaration/) ใหม่

## Remarks

หมายเหตุ: หาก [XmlDocument](../) ถูกบันทึกเป็น TextWriter หรือ [XmlTextWriter](../../xmltextwriter/) ค่าการเข้ารหัสนี้จะถูกละทิ้ง. แทนที่จะใช้การเข้ารหัสของ TextWriter หรือ [XmlTextWriter](../../xmltextwriter/). สิ่งนี้ทำให้ XML ที่เขียนออกมาสามารถอ่านได้กลับด้วยการเข้ารหัสที่ถูกต้อง.

## See Also

* typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlDeclaration](../../xmldeclaration/)
* คลาส [String](../../../system/string/)
* คลาส [XmlDocument](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)