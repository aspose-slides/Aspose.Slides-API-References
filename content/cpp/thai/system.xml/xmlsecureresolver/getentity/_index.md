---
title: GetEntity()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แมป URI ไปยังอ็อบเจ็กต์ที่บรรจุทรัพยากรจริง.
type: docs
weight: 27
url: /th/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) เมธอด


แมป URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริง.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่คืนจากการเรียก [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) |
| role | [String](../../../system/string/) | ปัจจุบันไม่ได้ใช้ |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของอ็อบเจ็กต์ที่จะคืน. รุ่นปัจจุบันจะคืนอ็อบเจ็กต์ประเภท Stream เท่านั้น. |

### ค่าที่คืน

สตรีมที่คืนโดยการเรียก **GetEntity** บน [XmlResolver](../../xmlresolver/) ที่อยู่ภายใต้. หากระบุประเภทที่ไม่ใช่ Stream เมธอดจะคืนค่า **nullptr**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlSecureResolver](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)