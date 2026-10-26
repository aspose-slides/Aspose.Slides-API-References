---
title: GetEntity()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: แมป URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง.
type: docs
weight: 14
url: /th/aspose.slides.import/externalresourceresolver/getentity/
---
## ExternalResourceResolver::GetEntity(System::String) เมธอด

แมป URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::ExternalResourceResolver::GetEntity(System::String absoluteUri) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | URI สมบูรณ์ของอ็อบเจกต์. |

### ค่าที่ส่งกลับ

อ็อบเจกต์ [System::IO::Stream](../../../system.io/stream/) หรือ null หากทรัพยากรไม่สามารถสตรีมได้.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [String](../../../system/string/)
* คลาส [ExternalResourceResolver](../)
* เนมสเปซ [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)