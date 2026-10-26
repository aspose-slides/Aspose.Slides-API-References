---
title: ToString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คืนค่าข้อความของ XmlQualifiedName.
type: docs
weight: 79
url: /th/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const เมธอด

คืนค่าข้อความของ [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### ค่าที่ส่งคืน

ค่าข้อความของ [XmlQualifiedName](../) ในรูปแบบ **namespace:localname**. หากอ็อบเจกต์ไม่มีการกำหนด namespace เมธอดนี้จะคืนค่าเฉพาะชื่อ local name เท่านั้น.

## XmlQualifiedName::ToString(const String\&, const String\&) เมธอด

คืนค่าข้อความของ [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | ชื่อของอ็อบเจกต์. |
| ns | const [String](../../../system/string/)\& | เนมสเปสของอ็อบเจกต์. |

### ค่าที่ส่งคืน

ค่าข้อความของ [XmlQualifiedName](../) ในรูปแบบ **namespace:localname**. หากอ็อบเจกต์ไม่มีการกำหนด namespace เมธอดนี้จะคืนค่าเฉพาะชื่อ local name เท่านั้น.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlQualifiedName](../)
* เนมสเปส [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)