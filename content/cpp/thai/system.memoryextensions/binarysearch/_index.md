---
title: BinarySearch()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ทำการค้นหาแบบไบนารีบนช่วงที่เรียงลำดับแล้ว.
type: docs
weight: 14
url: /th/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) ฟังก์ชัน

ทำการค้นหาแบบไบนารีบนช่วงที่เรียงลำดับแล้ว.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |
| TComparable | ประเภทของค่าที่เปรียบเทียบได้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ช่วงที่เรียงลำดับแล้วเพื่อทำการค้นหา |
| comparable | const TComparable\& | ค่าที่จะค้นหา |

### ค่าที่ส่งคืน

[Index](../../system/index/) ขององค์ประกอบที่พบ, หรือค่ากำหนดบิตแบบคอมพลีเมนต์ของตำแหน่งแทรกหากไม่พบ

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) ฟังก์ชัน

ทำการค้นหาแบบไบนารีบนช่วงที่เรียงลำดับโดยใช้ตัวเปรียบเทียบแบบกำหนดเอง.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |
| TComparer | ประเภทของตัวเปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ช่วงที่เรียงลำดับแล้วเพื่อทำการค้นหา |
| value | const T\& | ค่าที่จะค้นหา |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | ตัวเปรียบเทียบที่จะใช้สำหรับการเปรียบเทียบ |

### ค่าที่ส่งคืน

[Index](../../system/index/) ขององค์ประกอบที่พบ, หรือค่ากำหนดบิตแบบคอมพลีเมนต์ของตำแหน่งแทรกหากไม่พบ

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) ฟังก์ชัน

ทำการค้นหาแบบไบนารีบนช่วงที่จัดเรียงได้และเรียงลำดับแล้ว.

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |
| TComparable | ประเภทของค่าที่เปรียบเทียบได้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | ช่วงที่เรียงลำดับแล้วเพื่อทำการค้นหา |
| comparable | const TComparable\& | ค่าที่จะค้นหา |

### ค่าที่ส่งคืน

[Index](../../system/index/) ขององค์ประกอบที่พบ, หรือค่ากำหนดบิตแบบคอมพลีเมนต์ของตำแหน่งแทรกหากไม่พบ

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) ฟังก์ชัน

ทำการค้นหาแบบไบนารีบนช่วงที่จัดเรียงได้และเรียงลำดับแล้วโดยใช้ตัวเปรียบเทียบแบบกำหนดเอง.

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในช่วง |
| TComparer | ประเภทของตัวเปรียบเทียบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | ช่วงที่เรียงลำดับแล้วเพื่อทำการค้นหา |
| value | const T\& | ค่าที่จะค้นหา |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | ตัวเปรียบเทียบที่จะใช้สำหรับการเปรียบเทียบ |

### ค่าที่ส่งคืน

[Index](../../system/index/) ขององค์ประกอบที่พบ, หรือค่ากำหนดบิตแบบคอมพลีเมนต์ของตำแหน่งแทรกหากไม่พบ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)