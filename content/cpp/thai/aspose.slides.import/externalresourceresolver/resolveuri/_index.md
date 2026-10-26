---
title: ResolveUri()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: หาค่า URI แน่นอนจาก URI ฐานและ URI เชิงสัมพันธ์
type: docs
weight: 1
url: /th/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri(System::String, System::String) เมธอด

หาค่า URI แน่นอนจาก URI ฐานและ URI สัมพัทธ์.

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | URI ฐานของวัตถุที่เชื่อมโยง |
| relativeUri | [System::String](../../../system/string/) | URI เชิงสัมพันธ์ของวัตถุที่เชื่อมโยง |

### ค่าที่ส่งคืน

URI แน่นอนหรือ null หากไม่สามารถแก้ไข URI เชิงสัมพันธ์ได้.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ExternalResourceResolver](../)
* เนมสเปซ [Aspose::Slides::Import](../../)
* ไลบรารี [Aspose.Slides](../../../)