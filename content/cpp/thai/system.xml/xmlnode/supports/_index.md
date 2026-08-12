---
title: Supports()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทดสอบว่าโครงสร้าง DOM รองรับฟีเจอร์เฉพาะหรือไม่.
type: docs
weight: 482
url: /th/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) เมธอด

ทดสอบว่าโครงสร้าง DOM รองรับฟีเจอร์เฉพาะหรือไม่.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| feature | [String](../../../system/string/) | ชื่อแพ็กเกจของฟีเจอร์ที่ต้องการทดสอบ. ชื่อนี้ไม่สนใจตัวพิมพ์ใหญ่เล็ก. |
| version | [String](../../../system/string/) | หมายเลขเวอร์ชันของชื่อแพ็กเกจที่ต้องการทดสอบ. หากไม่ได้ระบุเวอร์ชัน (null) การสนับสนุนเวอร์ชันใด ๆ ของฟีเจอร์จะทำให้เมธอดส่งค่า **true**. |

### ค่าที่ส่งคืน

**true** if the feature is implemented in the specified version; otherwise, **false**.

## หมายเหตุ

ตารางต่อไปนี้อธิบายการรวมที่ให้ค่า **true**.

| ฟีเจอร์ | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNode](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)