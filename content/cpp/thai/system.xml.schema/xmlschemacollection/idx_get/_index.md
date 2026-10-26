---
title: idx_get()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืน XmlSchema ที่เชื่อมโยงกับ URI ของเนมสเปซที่กำหนด
type: docs
weight: 53
url: /th/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) เมธอด

คืนค่า [XmlSchema](../../xmlschema/) ที่เชื่อมโยงกับ URI ของเนมสเปซที่กำหนด.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI ของเนมสเปซที่เชื่อมโยงกับสคีมาที่คุณต้องการคืนค่า โดยทั่วไปจะเป็น **targetNamespace** ของสคีมา |

### ค่าที่คืน

The [XmlSchema](../../xmlschema/) ที่เชื่อมโยงกับ URI ของเนมสเปซ; **nullptr** หากไม่มีสคีมาที่โหลดไว้เชื่อมโยงกับเนมสเปซที่กำหนดหรือหากเนมสเปซเชื่อมโยงกับสคีมาชนิด XDR.

## ดูเพิ่มเติม

* typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [XmlSchema](../../xmlschema/)
* คลาส [String](../../../system/string/)
* คลาส [XmlSchemaCollection](../)
* เนมสเปซ [System::Xml::Schema](../../)
* ไลบรารี [Aspose.Slides](../../../)