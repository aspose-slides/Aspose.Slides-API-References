---
title: HasFeature()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทดสอบว่า implementation ของ Document Object Model (DOM) รองรับคุณลักษณะเฉพาะหรือไม่.
type: docs
weight: 14
url: /th/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) เมธอด


ทดสอบว่าโมเดล Document [Object](../../../system/object/) Implementation (DOM) ใช้คุณลักษณะเฉพาะหรือไม่

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | ชื่อแพคเกจของคุณลักษณะที่จะทดสอบ ชื่อนี้ไม่สนใจตัวพิมพ์ใหญ่หรือเล็ก |
| strVersion | const [String](../../../system/string/)\& | นี่คือหมายเลขเวอร์ชันของชื่อแพคเกจที่ต้องการทดสอบ หากไม่ได้ระบุเวอร์ชัน (**nullptr**), การสนับสนุนเวอร์ชันใดก็ของคุณลักษณะนี้ทำให้เมธอดคืนค่า **true** |

### ค่าที่ส่งคืน

**true** หากคุณลักษณะถูกนำไปใช้ในเวอร์ชันที่ระบุ; หากไม่เช่นนั้น, **false**.
## หมายเหตุ



ตารางต่อไปนี้แสดงการประกอบที่ทำให้ **HasFeature** คืนค่า **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlImplementation](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)