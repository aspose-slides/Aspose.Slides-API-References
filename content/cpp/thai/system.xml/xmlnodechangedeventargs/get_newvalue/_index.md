---
title: get_NewValue()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าค่าใหม่ของโหนด.
type: docs
weight: 66
url: /th/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() เมธอด

คืนค่าค่าใหม่ของโหนด.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### ค่าที่ส่งคืน

ค่ใหม่ของโหนด. เมธอดนี้จะคืนค่า **nullptr** หากโหนดไม่ใช่แอตทริบิวต์หรือโหนดข้อความ หรือหากโหนดกำลังถูกลบ. หากถูกเรียกในเหตุการณ์ **XmlDocument::NodeChanging** เมธอด **get_NewValue** จะคืนค่าของโหนดหากการเปลี่ยนแปลงสำเร็จ. หากถูกเรียกในเหตุการณ์ **XmlDocument::NodeChanged** เมธอด **get_NewValue** จะคืนค่าปัจจุบันของโหนด.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [XmlNodeChangedEventArgs](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)