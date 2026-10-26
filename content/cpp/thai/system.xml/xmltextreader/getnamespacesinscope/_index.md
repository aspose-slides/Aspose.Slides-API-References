---
title: GetNamespacesInScope()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ส่งคืนคอลเลกชันที่ประกอบด้วยเนมสเปซทั้งหมดที่อยู่ในขอบเขตในปัจจุบัน.
type: docs
weight: 716
url: /th/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) เมธอด

ส่งคืนคอลเลกชันที่ประกอบด้วยเนมสเปซทั้งหมดที่อยู่ในขอบเขตในปัจจุบัน.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | ค่าของ XmlNamespaceScope ที่ระบุประเภทของโหนดเนมสเปซที่ต้องการส่งคืน. |

### ค่าที่ส่งคืน

อ็อบเจ็กต์ IDictionary ที่ประกอบด้วยเนมสเปซทั้งหมดที่อยู่ในขอบเขตปัจจุบัน หากตัวอ่านไม่ได้อยู่บนองค์ประกอบใด จะส่งคืนพจนานุกรมว่าง (ไม่มีเนมสเปซ).

## ดูเพิ่มเติม

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [String](../../../system/string/)
* คลาส [XmlTextReader](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)