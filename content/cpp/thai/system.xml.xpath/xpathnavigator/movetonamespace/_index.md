---
title: MoveToNamespace()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ย้าย XPathNavigator ไปยังโหนดเนมสเปซโดยใช้คำนำหน้าชื่อเนมสเปซที่ระบุ
type: docs
weight: 547
url: /th/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace(String) เมธอด

Moves the [XPathNavigator](../) to the namespace node with the specified namespace prefix.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | [String](../../../system/string/) | คำนำหน้าชื่อเนมสเปซของโหนดเนมสเปซ |

### ค่าที่คืน

**true** หาก [XPathNavigator](../) ย้ายไปยังเนมสเปซที่ระบุสำเร็จ; **false** หากไม่พบโหนดเนมสเปซที่ตรงกัน หรือหาก [XPathNavigator](../) ไม่ได้อยู่บนโหนดองค์ประกอบ. หาก **false**, ตำแหน่งของ [XPathNavigator](../) จะไม่เปลี่ยนแปลง.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)