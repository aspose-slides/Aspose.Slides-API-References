---
title: ToLowerInvariant()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่คงที่.
type: docs
weight: 456
url: /th/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) ฟังก์ชัน


แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่คงที่.

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ช่วงอักขระต้นฉบับที่ต้องการแปลง |
| destination | [Span](../../system/span/)\<char16_t\>\& | ช่วงปลายทางเพื่อเก็บอักขระที่แปลงแล้ว |

### ค่าที่ส่งกลับ

จำนวนอักขระที่แปลงแล้ว หรือ -1 หากปลายทางมีขนาดไม่พอ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)