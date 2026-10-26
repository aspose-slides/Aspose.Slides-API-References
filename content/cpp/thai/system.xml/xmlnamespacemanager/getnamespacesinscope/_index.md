---
title: GetNamespacesInScope()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนคอลเลกชันของชื่อเนมส페ซที่มีคีย์เป็นคำนำหน้า ซึ่งสามารถใช้เพื่อแสดงรายการเนมส페ซที่อยู่ในขอบเขตปัจจุบัน
type: docs
weight: 105
url: /th/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) เมธอด

ส่งคืนคอลเลกชันของชื่อเนมส페ซที่มีคีย์เป็นคำนำหน้า ซึ่งสามารถใช้เพื่อวนรายการเนมส페ซที่อยู่ในขอบเขตในขณะนี้.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | ค่าที่เป็น enumeration ที่ระบุประเภทของโหนด namespace ที่จะคืนค่า. |

### ค่าที่ส่งคืน

คอลเลกชันของคู่ namespace และ prefix ที่อยู่ในขอบเขตในขณะนี้.

## ดูเพิ่มเติม

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDictionary](../../../system.collections.generic/idictionary/)
* คลาส [String](../../../system/string/)
* คลาส [XmlNamespaceManager](../)
* เนมส페ซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)