---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุสามค่าใน span.
type: docs
weight: 235
url: /th/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\>) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุสามค่าใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องไม่นับรวม |
| value1 | const T\& | ค่าที่สองที่ต้องไม่นับรวม |
| value2 | const T\& | ค่า τρίที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\>) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุสามค่าใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องไม่นับรวม |
| value1 | const T\& | ค่าที่สองที่ต้องไม่นับรวม |
| value2 | const T\& | ค่า τρίที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุสองค่าใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องไม่นับรวม |
| value1 | const T\& | ค่าที่สองที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุสองค่าใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องไม่นับรวม |
| value1 | const T\& | ค่าที่สองที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุหนึ่งค่าใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value | const T\& | ค่าที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าที่ระบุหนึ่งค่าใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value | const T\& | ค่าที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าจากลำดับหนึ่งใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับของค่าที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าจากลำดับหนึ่งใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับของค่าที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของสมาชิกใด ๆ ที่ไม่ใช่ค่าจากลำดับที่สามารถแก้ไขได้ใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [Span](../../system/span/)\<T\>\& | ลำดับของค่าที่ต้องไม่นับรวม |

### ค่าที่ส่งคืน

ดัชนีแบบศูนย์ของสมาชิกสุดท้ายที่ไม่ถูกตัดออก, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)