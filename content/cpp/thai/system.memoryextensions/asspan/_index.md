---
title: AsSpan()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้าง span จากอาร์เรย์.
type: docs
weight: 1
url: /th/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) ฟังก์ชัน

สร้าง span จากอาร์เรย์.

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในอาร์เรย์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | อาร์เรย์ต้นทาง. |
| start | **int32_t** | ดัชนีเริ่มต้นในอาร์เรย์. |
| length | **int32_t** | ความยาวของ span. |

### ค่าที่ส่งคืน

Span<T> ครอบส่วนที่ระบุของอาร์เรย์.

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) ฟังก์ชัน

สร้าง span แบบอ่านอย่างเดียวจากสตริง.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | สตริงต้นทาง. |
| start | **int32_t** | ดัชนีเริ่มต้นในสตริง. |
| length | **int32_t** | ความยาวของ span. |

### ค่าที่ส่งคืน

ReadOnlySpan<char16_t> ครอบส่วนที่ระบุของสตริง.

## ดูเพิ่มเติม

* ชนิดนิยาม [ArrayPtr](../../system/arrayptr/)
* คลาส [Span](../../system/span/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [String](../../system/string/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)