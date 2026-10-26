---
title: CompareTo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบช่วงอักขระสองช่วงด้วยกฎการเปรียบเทียบสตริงที่ระบุ
type: docs
weight: 404
url: /th/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) ฟังก์ชัน


เปรียบเทียบช่วงอักขระสองช่วงด้วยกฎการเปรียบเทียบสตริงที่ระบุ

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ช่วงอักขระแรก |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ช่วงอักขระที่สอง |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทของการเปรียบเทียบสตริงที่จะทำ |

### ค่าที่ส่งกลับ

ค่าติดลบหาก span < other, ศูนย์หากเท่ากัน, ค่าบวกหาก span > other

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* เนมสเปซ [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)