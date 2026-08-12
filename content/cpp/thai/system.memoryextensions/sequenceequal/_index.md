---
title: SequenceEqual()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: กำหนดว่าทั้งสอง ReadOnlySpan มีองค์ประกอบที่เหมือนกันในลำดับเดียวกันหรือไม่.
type: docs
weight: 326
url: /th/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

กำหนดว่าทั้งสอง ReadOnlySpan มีองค์ประกอบที่เหมือนกันในลำดับเดียวกันหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span แรกที่ต้องเปรียบเทียบ |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span ที่สองที่ต้องเปรียบเทียบ |

### ค่าที่คืน

true หาก span มีความยาวเท่ากันและทุกองค์ประกอบเท่ากัน, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

กำหนดว่าหนึ่ง [Span](../../system/span/) และ [ReadOnlySpan](../../system/readonlyspan/) มีองค์ประกอบที่เหมือนกันในลำดับเดียวกันหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่ต้องเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่ต้องเปรียบเทียบ |

### ค่าที่คืน

true หาก span มีความยาวเท่ากันและทุกองค์ประกอบเท่ากัน, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) ฟังก์ชัน

กำหนดว่าทั้งสอง ReadOnlySpan มีองค์ประกอบที่เท่ากันโดยใช้ตัวเปรียบเทียบแบบกำหนดเอง

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |
| TComparer | ชนิดของอ็อบเจ็กต์ตัวเปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span แรกที่ต้องเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span ที่สองที่ต้องเปรียบเทียบ |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | ตัวชี้อัจฉริยะไปยังอ็อบเจ็กต์ตัวเปรียบเปรียบเทียบสำหรับการเปรียบเทียบองค์ประกอบ |

### ค่าที่คืน

true หาก span มีความยาวเท่ากันและตัวเปรียบเทียบพิจารณาทุกองค์ประกอบเท่ากัน, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) ฟังก์ชัน

กำหนดว่า [Span](../../system/span/) และ [ReadOnlySpan](../../system/readonlyspan/) มีองค์ประกอบที่เท่ากันโดยใช้ตัวเปรียบเทียบแบบกำหนดเอง

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |
| TComparer | ชนิดของอ็อบเจ็กต์ตัวเปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่ต้องเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่ต้องเปรียบเทียบ |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | ตัวชี้อัจฉริยะไปยังอ็อบเจ็กต์ตัวเปรียบเทียบสำหรับการเปรียบเทียบองค์ประกอบ |

### ค่าที่คืน

true หาก span มีความยาวเท่ากันและตัวเปรียบเทียบพิจารณาทุกองค์ประกอบเท่ากัน, false หากไม่เป็นเช่นนั้น

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)