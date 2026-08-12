---
title: ContainsAnyExcept()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุสามค่า.
type: docs
weight: 66
url: /th/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุสามค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| value0 | const T\& | ค่าที่จะยกเว้นค่าแรก |
| value1 | const T\& | ค่าที่จะยกเว้นค่าที่สอง |
| value2 | const T\& | ค่าที่จะยกเว้นค่าที่สาม |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบแก้ไขได้มีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุสามค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| value0 | const T\& | ค่าที่จะยกเว้นค่าแรก |
| value1 | const T\& | ค่าที่จะยกเว้นค่าที่สอง |
| value2 | const T\& | ค่าที่จะยกเว้นค่าที่สาม |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุสองค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| value0 | const T\& | ค่าที่จะยกเว้นค่าแรก |
| value1 | const T\& | ค่าที่จะยกเว้นค่าที่สอง |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบแก้ไขได้มีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุสองค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| value0 | const T\& | ค่าที่จะยกเว้นค่าแรก |
| value1 | const T\& | ค่าที่จะยกเว้นค่าที่สอง |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุหนึ่งค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| value | const T\& | ค่าที่จะยกเว้น |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

ตรวจสอบว่า span แบบแก้ไขได้มีองค์ประกอบใดที่ไม่ใช่ค่าที่ระบุหนึ่งค่า.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| value | const T\& | ค่าที่จะยกเว้น |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่แตกต่างจากค่าที่ระบุ, false มิฉะนั้น

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดที่ไม่อยู่ใน span อื่น.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน spans |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ของค่าที่จะยกเว้น |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่ไม่อยู่ใน values, false มิฉะเลย

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า span แบบแก้ไขได้มีองค์ประกอบใดที่ไม่อยู่ใน span แบบอ่านอย่างเดียว.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน spans |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แบบอ่านอย่างเดียวของค่าที่จะยกเว้น |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่ไม่อยู่ใน values, false มิฉะเลย

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)