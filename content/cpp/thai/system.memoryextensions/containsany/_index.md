---
title: ContainsAny()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบว่า span แบบอ่านอย่างเดียวมีค่าใดจากสองค่าหรือไม่.
type: docs
weight: 53
url: /th/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีค่าหนึ่งในสองค่าหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ต้องการค้นหา |
| value0 | const T\& | ค่าที่แรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีค่าใดหนึ่งในสามค่าหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ต้องการค้นหา |
| value0 | const T\& | ค่าที่แรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span ที่สามารถแก้ไขได้มีค่าหนึ่งในสองค่าหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่สามารถแก้ไขได้ |
| value0 | const T\& | ค่าที่แรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) function

ตรวจสอบว่า span ที่สามารถแก้ไขได้มีค่าใดหนึ่งในสามค่าหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่สามารถแก้ไขได้ |
| value0 | const T\& | ค่าที่แรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีค่าใดจาก span อื่นหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ต้องการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ของค่าที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า span ที่สามารถแก้ไขได้มีค่าใดจาก span แบบอ่านอย่างเดียวหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่ต้องการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แบบอ่านอย่างเดียวของค่าที่ต้องการค้นหา |

### ค่าที่คืน

true ถ้าพบค่าหนึ่งใดใน span, false หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)