---
title: LastIndexOf()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ค้นหาการเกิดขึ้นครั้งสุดท้ายของลำดับภายใน span.
type: docs
weight: 209
url: /th/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการเกิดขึ้นครั้งสุดท้ายของลำดับภายใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ของการเกิดขึ้นครั้งสุดท้าย หรือ -1 ถ้าไม่พบ

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาการเกิดขึ้นครั้งสุดท้ายของค่าตัวเดียวภายใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| value | const T\& | ค่าที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ของการเกิดขึ้นครั้งสุดท้าย หรือ -1 ถ้าไม่พบ

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการเกิดขึ้นครั้งสุดท้ายของลำดับภายใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ของการเกิดขึ้นครั้งสุดท้าย หรือ -1 ถ้าไม่พบ

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาการเกิดขึ้นครั้งสุดท้ายของค่าตัวเดียวภายใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| value | const T\& | ค่าที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ของการเกิดขึ้นครั้งสุดท้าย หรือ -1 ถ้าไม่พบ

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) ฟังก์ชัน

ค้นหาการเกิดขึ้นครั้งสุดท้ายของค่าภายใน span โดยใช้การเปรียบเทียบสตริงที่ระบุ.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span ที่จะค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ค่าที่จะค้นหา |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทของการเปรียบเทียบสตริงที่จะทำ |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ของการเกิดขึ้นครั้งสุดท้าย หรือ -1 ถ้าไม่พบ

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)