---
title: IndexOfAnyExcept()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุใน ReadOnlySpan<T>
type: docs
weight: 170
url: /th/system.memoryextensions/indexofanyexcept/
---
## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุใน ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value | const T\& | ค่าที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุสองค่าใน ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการยกเว้นจากการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุสามค่าใน ReadOnlySpan\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการยกเว้นจากการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการยกเว้นจากการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุใน Span\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value | const T\& | ค่าที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุสองค่าใน Span\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการยกเว้นจากการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุสามค่าใน Span\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่ต้องการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการยกเว้นจากการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการยกเว้นจากการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่อยู่ในสแปนของค่าใดค่าหนึ่ง

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปนหลายตัว |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่บรรจุค่าที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่ไม่เท่ากับค่าที่อยู่ในสแปนของค่าใดค่าหนึ่งใน Span\<T\>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปนหลายตัว |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่ต้องการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่บรรจุค่าที่ต้องการยกเว้นจากการค้นหา |

### ค่าที่ส่งกลับ

ดัชนีเริ่มต้นจากศูนย์ขององค์ประกอบแรกที่ไม่ตรงกัน, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)