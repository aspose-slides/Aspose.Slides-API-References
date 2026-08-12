---
title: LookupPrefix()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าคำนำหน้าที่ประกาศไว้สำหรับ URI ของเนมสเปซที่ระบุ.
type: docs
weight: 417
url: /th/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) เมธอด


คืนค่าคำนำหน้าที่ประกาศไว้สำหรับ URI ของเนมสเปซที่ระบุ

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | URI ของเนมสเปซที่จะใช้เพื่อแก้ไขคำนำหน้า |

### ค่าที่ส่งคืน

อ็อบเจกต์ [String](../../../system/string/) ที่มีคำนำหน้าของเนมสเปซที่กำหนดให้กับ URI ของเนมสเปซที่ระบุ; หากไม่มีคำนำหน้าถูกกำหนดให้กับ URI ของเนมสปลซ์ที่ระบุ, จะได้ค่า [String::Empty](../../../system/string/empty/). [String](../../../system/string/) ที่ส่งคืนจะถูกทำให้เป็นอะตอม

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XPathNavigator](../)
* เนมสเปซ [System::Xml::XPath](../../)
* ไลบรารี [Aspose.Slides](../../../)