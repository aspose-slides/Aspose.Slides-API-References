---
title: get_OldValue()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าต้นฉบับของโหนด.
type: docs
weight: 53
url: /th/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() เมธอด


คืนค่าต้นฉบับของโหนด.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### ค่าที่ส่งคืน

ค่าต้นฉบับของโหนด. เมธอดนี้คืนค่า **nullptr** หากโหนดไม่ใช่แอตทริบิวต์หรือโหนดข้อความ, หรือหากโหนดกำลังถูกแทรก. หากเรียกในเหตุการณ์ **XmlDocument::NodeChanging**, **get_OldValue** จะคืนค่าปัจจุบันของโหนดที่จะถูกแทนที่หากการเปลี่ยนแปลงสำเร็จ. หากเรียกในเหตุการณ์ **XmlDocument::NodeChanged**, **get_OldValue** จะคืนค่าของโหนดก่อนการเปลี่ยนแปลง.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeChangedEventArgs](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)