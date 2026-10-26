---
title: GetEntity()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เมื่อถูก override ในคลาสที่สืบทอด จะทำการแม็พ URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริงอยู่
type: docs
weight: 14
url: /th/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

เมื่อถูก override ในคลาสที่สืบทอด จะทำการแม็พ URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริงอยู่

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่ส่งคืนจากการเรียก [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) |
| role | [String](../../../system/string/) | ปัจจุบันไม่ได้ใช้ |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของอ็อบเจ็กต์ที่จะส่งกลับ รุ่นปัจจุบันจะส่งคืนอ็อบเจ็กต์ประเภท Stream เท่านั้น |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ Stream หรือ **nullptr** หากระบุประเภทที่ไม่ใช่ stream

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlResolver](../)
* เนมสเปซ [System::Xml](../../)
* Library [Aspose.Slides](../../../)