---
title: GetEntity()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แมป URI ไปยังอ็อบเจ็กต์ที่บรรจุทรัพยากรจริง.
type: docs
weight: 53
url: /th/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

แมป URI ไปยังอ็อบเจ็กต์ที่บรรจุทรัพยากรจริง

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ที่ส่งคืนจากการเรียก [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) |
| role | [String](../../../system/string/) | ปัจจุบันไม่ได้ใช้ |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | ประเภทของอ็อบเจ็กต์ที่ต้องการคืนค่า การทำงานปัจจุบันจะคืนค่าอ็อบเจ็กต์ประเภท Stream เท่านั้น |

### ค่าที่คืน

อ็อบเจ็กต์ประเภท stream หรือ **nullptr** หากระบุประเภทที่ไม่ใช่ stream

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Object](../../../system/object/)
* คลาส [Uri](../../../system/uri/)
* คลาส [String](../../../system/string/)
* คลาส [TypeInfo](../../../system/typeinfo/)
* คลาส [XmlUrlResolver](../)
* เนมสเปซ [System::Xml](../../)
* ไลบรารี [Aspose.Slides](../../../)