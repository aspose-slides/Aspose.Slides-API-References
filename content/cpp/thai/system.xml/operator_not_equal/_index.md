---
title: operator!=()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เปรียบเทียบวัตถุ XmlQualifiedName สองรายการ.
type: docs
weight: 612
url: /th/system.xml/operator_not_equal/
---
## System::Xml::operator!=(const SharedPtr\<XmlQualifiedName\>\&, const SharedPtr\<XmlQualifiedName\>\&) ฟังก์ชัน

เปรียบเทียบวัตถุ [XmlQualifiedName](../xmlqualifiedname/) สองรายการ.

```cpp
bool System::Xml::operator!=(const SharedPtr<XmlQualifiedName> &a, const SharedPtr<XmlQualifiedName> &b)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../xmlqualifiedname/)\>\& | [XmlQualifiedName](../xmlqualifiedname/) สำหรับเปรียบเทียบ |
| b | const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../xmlqualifiedname/)\>\& | [XmlQualifiedName](../xmlqualifiedname/) สำหรับเปรียบเทียบ |

### ค่าที่ส่งกลับ

**true** หากค่า name และ namespace ของวัตถุสองอันแตกต่างกัน; มิฉะนั้น **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [XmlQualifiedName](../xmlqualifiedname/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)