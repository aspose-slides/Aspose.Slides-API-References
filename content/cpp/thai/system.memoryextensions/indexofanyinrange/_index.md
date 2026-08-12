---
title: IndexOfAnyInRange()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหาดัชนีขององค์ประกอบแรกที่อยู่ในช่วงที่ระบุใน ReadOnlySpan<T>
type: docs
weight: 196
url: /th/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่อยู่ในช่วงที่ระบุใน ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| lowInclusive | const T\& | ขอบล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบบนของช่วง (รวม) |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ขององค์ประกอบแรกในช่วง, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบแรกที่อยู่ในช่วงที่ระบุใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะค้นหา |
| lowInclusive | const T\& | ขอบล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบบนของช่วง (รวม) |

### ค่าที่ส่งกลับ

ดัชนีเริ่มจากศูนย์ขององค์ประกอบแรกในช่วง, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)