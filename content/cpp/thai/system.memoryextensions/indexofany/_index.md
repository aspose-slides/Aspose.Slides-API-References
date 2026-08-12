---
title: IndexOfAny()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าที่ระบุสองค่าจาก ReadOnlySpan<T>
type: docs
weight: 157
url: /th/system.memoryextensions/indexofany/
---
## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าที่ระบุสองค่าจาก `ReadOnlySpan<T>`

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการค้นหา |
| value1 | const T\& | ค่า第二ที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าที่ระบุสามค่าจาก `ReadOnlySpan<T>`

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าที่ระบุสองค่าจาก `Span<T>`

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าที่ระบุสามค่าจาก `Span<T>`

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| value0 | const T\& | ค่าแรกที่ต้องการค้นหา |
| value1 | const T\& | ค่าที่สองที่ต้องการค้นหา |
| value2 | const T\& | ค่าที่สามที่ต้องการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## System::MemoryExtensions::IndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าจาก span หนึ่งใน `ReadOnlySpan<T>` อีกอัน

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน spans |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่บรรจุตัวค่าเพื่อทำการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## System::MemoryExtensions::IndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาตำแหน่งดัชนีของการปรากฏเป็นครั้งแรกของค่าจาก span หนึ่งใน `Span<T>`

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน spans |

### อากิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะทำการค้นหา |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่บรรจุตัวค่าเพื่อทำการค้นหา |

### ค่าที่ส่งกลับ

ค่าดัชนีเริ่มจากศูนย์ของการปรากฏครั้งแรก, หรือ -1 หากไม่พบ


## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)