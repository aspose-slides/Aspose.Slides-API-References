---
title: ToLower()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่ระบุ.
type: docs
weight: 443
url: /th/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) function


แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่ระบุ.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ช่วงอักขระต้นฉบับที่ต้องการแปลง |
| destination | [Span](../../system/span/)\<char16_t\>\& | ช่วงปลายทางเพื่อเก็บอักขระที่แปลงแล้ว |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่ใช้สำหรับการแปลง (nullptr สำหรับวัฒนธรรมปัจจุบัน) |

### คืนค่า

จำนวนอักขระที่แปลงแล้ว, หรือ -1 หากปลายทางมีขนาดเล็กเกินไป

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* คลาส [CultureInfo](../../system.globalization/cultureinfo/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)