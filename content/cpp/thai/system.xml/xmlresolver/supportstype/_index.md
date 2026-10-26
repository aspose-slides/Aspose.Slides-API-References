---
title: SupportsType()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: ทำให้ตัวแก้ไขสามารถคืนค่าชนิดอื่นนอกจาก Stream.
type: docs
weight: 40
url: /th/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) เมธอด

ทำให้ตัวแก้ไขสามารถคืนค่าชนิดอื่นนอกจาก Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | ชนิดที่จะคืนค่า. |

### ค่าที่ส่งกลับ

**true** ถ้า **type** ได้รับการสนับสนุน; มิฉะนั้น, **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Uri](../../../system/uri/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlResolver](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)