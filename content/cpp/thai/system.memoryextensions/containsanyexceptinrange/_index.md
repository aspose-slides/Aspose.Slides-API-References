---
title: ContainsAnyExceptInRange()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดอยู่นอกช่วงที่ระบุหรือไม่
type: docs
weight: 79
url: /th/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ตรวจสอบว่ามี span แบบอ่านอย่างเดียวที่มีองค์ประกอบใดอยู่นอกช่วงที่ระบุหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span (ต้องสามารถเปรียบเทียบได้) |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| lowInclusive | const T\& | ขอบล่าง (รวม) |
| highInclusive | const T\& | ขอบบน (รวม) |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่อยู่นอกช่วง, false ในกรณีอื่น

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ตรวจสอบว่า span ที่เปลี่ยนแปลงได้มีองค์ประกอบใดที่อยู่นอกช่วงที่ระบุหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span (ต้องสามารถเปรียบเทียบได้) |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่เปลี่ยนแปลงได้ที่จะค้นหา |
| lowInclusive | const T\& | ขอบล่าง (รวม) |
| highInclusive | const T\& | ขอบบน (รวม) |

### ค่าที่ส่งกลับ

true หากพบองค์ประกอบใดที่อยู่นอกช่วง, false ในกรณีอื่น

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)