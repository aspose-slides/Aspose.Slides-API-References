---
title: ToUpperInvariant()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงอักขระเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมคงที่.
type: docs
weight: 482
url: /th/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) ฟังก์ชัน

แปลงอักษรเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมที่คงที่.

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ช่วงอักขระ source ที่ต้องแปลง |
| destination | [Span](../../system/span/)\<char16_t\>\& | ช่วง destination เพื่อเก็บอักขระที่แปลงแล้ว |

### คืนค่า

จำนวนอักขระที่แปลงแล้ว, หรือ -1 หาก destination มีขนาดเล็กเกินไป

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)