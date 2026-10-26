---
title: GetEntity()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แมป URI ไปยังอ็อบเจกต์ที่บรรจุทรัพยากรจริง
type: docs
weight: 53
url: /th/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) เมธอด

ทำการแมป URI ไปยังอ็อบเจกต์ที่บรรจุทรัพยากรจริง

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่ถูกคืนจากการเรียก [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) |
| role | [String](../../../system/string/) | ปัจจุบันไม่ได้ใช้ |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของอ็อบเจกต์ที่ต้องการคืนค่า. [XmlPreloadedResolver](../) รองรับอ็อบเจกต์ Stream และอ็อบเจกต์ TextReader สำหรับ URI ที่ถูกเพิ่มเป็น [String](../../../system/string/). หากประเภทที่ร้องขอไม่รองรับโดย resolver จะเกิดข้อยกเว้น. ใช้เมธอด XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) เพื่อกำหนดว่า **Type** ใดรองรับโดย resolver นี้. |

### ค่าที่คืนกลับ

อ็อบเจกต์ Stream หรือ TextReader ที่สอดคล้องกับแหล่งข้อมูลจริง

## ดูเพิ่มเติม

* typedef [SharedPtr](../../../system/sharedptr/)
* class [Object](../../../system/object/)
* class [Uri](../../../system/uri/)
* class [String](../../../system/string/)
* class [TypeInfo](../../../system/typeinfo/)
* class [XmlPreloadedResolver](../)
* namespace [System::Xml::Resolvers](../../)
* library [Aspose.Slides](../../../)