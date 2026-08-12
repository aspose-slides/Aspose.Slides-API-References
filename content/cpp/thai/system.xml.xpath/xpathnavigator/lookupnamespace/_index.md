---
title: LookupNamespace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืน URI ของเนมสเปซสำหรับคำนำหน้าที่ระบุ
type: docs
weight: 404
url: /th/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) เมธอด


ส่งคืน URI ของเนมสเปซสำหรับคำนำหน้าที่ระบุ

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าที่คุณต้องการแก้ไข URI ของเนมสเปซ หากต้องการจับคู่กับเนมสเปซเริ่มต้น ให้ส่ง [String::Empty](../../../system/string/empty/). |

### ค่าที่ส่งคืน

A [String](../../../system/string/) ที่มี URI ของเนมสเปซที่กำหนดให้กับคำนำหน้าที่ระบุ; **nullptr** หากไม่มี URI ของเนมสเปซที่กำหนดให้กับคำนำหน้าที่ระบุ. The [String](../../../system/string/) ที่ส่งคืนเป็นแบบ atomized.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)