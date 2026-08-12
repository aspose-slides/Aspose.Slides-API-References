---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบ ReadOnlySpan<char16_t> สองอันเพื่อความเท่าเทียมโดยใช้ StringComparison.
type: docs
weight: 417
url: /th/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

เปรียบเทียบ ReadOnlySpan<char16_t> สองอันเพื่อความเท่าเทียมโดยใช้ StringComparison.

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สเปนแรกที่จะเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สเปนที่สองที่จะเปรียบเทียบ |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทการเปรียบเทียบสตริงที่ใช้ |

### ค่าที่ส่งกลับ

true ถ้าสเปนเท่ากัน, false หากไม่เท่าเทียม

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)