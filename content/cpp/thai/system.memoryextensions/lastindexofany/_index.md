---
title: LastIndexOfAny()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากสามค่าที่ระบุภายใน span.
type: docs
weight: 222
url: /th/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากสามค่าที่ระบุภายใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าที่แรกที่จะค้นหา |
| value1 | const T\& | ค่าที่สองที่จะค้นหา |
| value2 | const T\& | ค่าที่สามที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากสามค่าที่ระบุภายใน mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าที่แรกที่จะค้นหา |
| value1 | const T\& | ค่าที่สองที่จะค้นหา |
| value2 | const T\& | ค่าที่สามที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากสองค่าที่ระบุภายใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าที่แรกที่จะค้นหา |
| value1 | const T\& | ค่าที่สองที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากสองค่าที่ระบุภายใน mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าที่แรกที่จะค้นหา |
| value1 | const T\& | ค่าที่สองที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากลำดับภายใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับของค่าที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากลำดับภายใน mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ลำดับของค่าที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายของค่าใดค่าหนึ่งจากลำดับที่สามารถเปลี่ยนแปลงได้ภายใน mutable span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [Span](../../system/span/)\<T\>\& | ลำดับของค่าที่จะค้นหา |

### ค่าที่ส่งกลับ

ดัชนีที่เริ่มจากศูนย์ของการปรากฏครั้งสุดท้าย, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)