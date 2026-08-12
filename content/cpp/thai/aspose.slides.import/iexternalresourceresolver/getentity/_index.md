---
title: GetEntity()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แมป URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง.
type: docs
weight: 14
url: /th/aspose.slides.import/iexternalresourceresolver/getentity/
---
## IExternalResourceResolver::GetEntity(System::String) method


แมป URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง.

```cpp
virtual System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::IExternalResourceResolver::GetEntity(System::String absoluteUri)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI แน่นอนของอ็อบเจกต์. |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [System::IO::Stream](../../../system.io/stream/) หรือ null หากไม่สามารถสตรีมทรัพยากรได้.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)