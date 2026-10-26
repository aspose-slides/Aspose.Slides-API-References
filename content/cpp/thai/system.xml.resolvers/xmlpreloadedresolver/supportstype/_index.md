---
title: SupportsType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าตัว resolver รองรับ Types อื่นนอกจาก Stream หรือไม่.
type: docs
weight: 66
url: /th/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) เมธอด

กำหนดว่าตัว resolver รองรับ Types อื่นนอกจาก Stream หรือไม่.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI แบบเต็มที่ต้องตรวจสอบ. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทที่ต้องการส่งคืน. |

### ค่าที่คืน

**true** ถ้า Type ได้รับการสนับสนุน; หากไม่เช่นนั้น, **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlPreloadedResolver](../)
* เนมส페ซ [System::Xml::Resolvers](../../)
* ไลบรารี [Aspose.Slides](../../../)