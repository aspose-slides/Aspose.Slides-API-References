---
title: LookupNamespace()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืน URI ของเนมสเปซสำหรับคำนำหน้าที่ระบุ
type: docs
weight: 118
url: /th/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) เมธอด

ส่งคืน URI ของเนมสเปซสำหรับคำนำหน้าที่ระบุ

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | คำนำหน้าที่คุณต้องการแก้ไข URI ของเนมสเปซ. เพื่อให้ตรงกับเนมสเปซเริ่มต้น, ให้ส่ง [String::Empty](../../../system/string/empty/). |

### ค่าที่ส่งคืน

URI ของเนมสเปซสำหรับ **prefix** หรือ **nullptr** หากไม่มีเนมสเปซที่แมปไว้. สตริงที่ส่งคืนเป็นแบบ atomized. สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่ atomized, ดูคลาส [XmlNameTable](../../xmlnametable/).

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNamespaceManager](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)