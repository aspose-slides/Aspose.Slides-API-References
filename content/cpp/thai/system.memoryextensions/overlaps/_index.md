---
title: Overlaps()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดว่ามี ReadOnlySpans สองตัวทับซ้อนกันในหน่วยความจำหรือไม่โดยไม่คำนวณระยะห่าง
type: docs
weight: 274
url: /th/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน


กำหนดว่า ReadOnlySpans สองตัวทับซ้อนกันในหน่วยความจำหรือไม่โดยไม่คำนวณระยะห่าง

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แรกที่ต้องตรวจสอบการทับซ้อน |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่สองที่ต้องตรวจสอบการทับซ้อน |

### ค่าที่คืนกลับ

true หาก span มีตำแหน่งหน่วยความจำร่วมกัน, false ในกรณีอื่น

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน


กำหนดว่า [Span](../../system/span/) และ [ReadOnlySpan](../../system/readonlyspan/) ทับซ้อนกันในหน่วยความจำหรือไม่โดยไม่คำนวณระยะห่าง

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่ต้องตรวจสอบการทับซ้อน |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่ต้องตรวจสอบการทับซ้อน |

### ค่าที่คืนกลับ

true หาก span มีตำแหน่งหน่วยความจำร่วมกัน, false ในกรณีอื่น

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) ฟังก์ชัน


กำหนดว่า ReadOnlySpans สองตัวทับซ้อนกันในหน่วยความจำและคำนวณระยะห่าง

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แรกที่ต้องตรวจสอบการทับซ้อน |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่สองที่ต้องตรวจสอบการทับซ้อน |
| elementOffset | **int32_t**\& | พารามิเตอร์ผลลัพธ์ที่รับระยะห่างระหว่าง span หากมันทับซ้อนกัน |

### ค่าที่คืนกลับ

true หาก span มีตำแหน่งหน่วยความจำร่วมกัน, false ในกรณีอื่น

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) ฟังก์ชัน


กำหนดว่า [Span](../../system/span/) และ [ReadOnlySpan](../../system/readonlyspan/) ทับซ้อนกันในหน่วยความจำและคำนวณระยะห่าง

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```


### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่ต้องตรวจสอบการทับซ้อน |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่ต้องตรวจสอบการทับซ้อน |
| elementOffset | **int32_t**\& | พารามิเตอร์ผลลัพธ์ที่รับระยะห่างระหว่าง span หากมันทับซ้อนกัน |

### ค่าที่คืนกลับ

true หาก span มีตำแหน่งหน่วยความจำร่วมกัน, false ในกรณีอื่น

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)