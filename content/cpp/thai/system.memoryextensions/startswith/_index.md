---
title: StartsWith()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่า span เริ่มต้นด้วยค่าที่ระบุหรือไม่.
type: docs
weight: 352
url: /th/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ตรวจสอบว่า span เริ่มต้นด้วยค่าที่กำหนดหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const T\& | ค่าที่จะตรวจสอบที่จุดเริ่มต้นของ span |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยค่า, false ในกรณีอื่น

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตรวจสอบว่า span เริ่มต้นด้วย span ของค่าที่ระบุหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน spans |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่มีค่าที่จะตรวจสอบที่จุดเริ่มต้น |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยค่า span, false ในกรณีอื่น

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตรวจสอบว่า span ที่เปลี่ยนแปลงได้เริ่มต้นด้วย span ของค่าที่เป็นแบบอ่านอย่างเดียวที่ระบุหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน spans |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่เปลี่ยนแปลงได้ที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แบบอ่านอย่างเดียวที่มีค่าที่จะตรวจสอบ |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยค่า span, false ในกรณีอื่น

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) ฟังก์ชัน

ตรวจสอบว่า span แบบอ่านอย่างเดียวเริ่มต้นด้วย span ของค่าที่เปลี่ยนแปลงได้ที่ระบุหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน spans |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แบบอ่านอย่างเดียวที่จะตรวจสอบ |
| value | const [Span](../../system/span/)\<T\>\& | span ที่เปลี่ยนแปลงได้ที่มีค่าที่จะตรวจสอบ |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยค่า span, false ในกรณีอื่น

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) ฟังก์ชัน

ตรวจสอบว่า span ของอักขระเริ่มต้นด้วยค่า span ที่ระบุโดยใช้การเปรียบเทียบสตริง.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span ของอักขระที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span ของอักขระที่มีค่าที่จะตรวจสอบ |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทของการเปรียบเทียบสตริงที่จะทำ |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยค่า span, false ในกรณีอื่น

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) ฟังก์ชัน

ตรวจสอบว่า span ของสตริงเริ่มต้นด้วยอาเรย์อักขระที่ระบุหรือไม่.

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | span ของสตริงที่จะตรวจสอบ |
| val | const char16_t * | อาเรย์อักขระที่จะตรวจสอบที่จุดเริ่มต้น |

### ค่าที่ส่งคืน

true หาก span เริ่มต้นด้วยอาเรย์อักขระ, false ในกรณีอื่น

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* คลาส [String](../../system/string/)
* เนมสเปซ [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)