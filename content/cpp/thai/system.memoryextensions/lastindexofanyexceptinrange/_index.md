---
title: LastIndexOfAnyExceptInRange()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ที่อยู่นอกช่วงที่ระบุภายในช่วง
type: docs
weight: 248
url: /th/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ที่อยู่นอกช่วงที่กำหนดภายในช่วง

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ช่วงที่ใช้ในการค้นหา |
| lowInclusive | const T\& | ขอบเขตล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบเขตบนของช่วง (รวม) |

### ค่าที่คืนกลับ

ดัชนีเริ่มจากศูนย์ขององค์ประกอบสุดท้ายที่อยู่นอกช่วง, หรือ -1 หากไม่พบ

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ที่อยู่นอกช่วงที่กำหนดภายในช่วงที่สามารถเปลี่ยนแปลงได้

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | ช่วงที่ใช้ในการค้นหา |
| lowInclusive | const T\& | ขอบเขตล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบเขตบนของช่วง (รวม) |

### ค่าที่คืนกลับ

ดัชนีเริ่มจากศูนย์ขององค์ประกอบสุดท้ายที่อยู่นอกช่วง, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)