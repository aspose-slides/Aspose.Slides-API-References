---
title: CommonPrefixLength()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ค้นหาความยาวของคำนำร่วมระหว่างสองสแปน
type: docs
weight: 27
url: /th/system.memoryextensions/commonprefixlength/
---
## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสองสแปน

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนแรก |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่สอง |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสแปนที่สามารถแก้ไขได้และสแปนที่อ่านอย่างเดียว

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนอ่านอย่างเดียว |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสองสแปนที่สามารถแก้ไขได้

```cpp
template<typename T> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้แรก |
| other | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่สอง |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสองสแปนโดยใช้ตัวเปรียบเทียบความเท่าเทียมแบบกำหนดเอง

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |
| TEqualityComparer | ประเภทของตัวเปรียบเทียบความเท่าเทียม |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนแรก |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่สอง |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | ตัวเปรียบเทียบความเท่าเทียมที่จะใช้สำหรับการเปรียบเทียบองค์ประกอบ |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสแปนที่สามารถแก้ไขได้และสแปนที่อ่านอย่างเดียวโดยใช้ตัวเปรียบเทียบความเท่าเทียมแบบกำหนดเอง

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const ReadOnlySpan<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |
| TEqualityComparer | ประเภทของตัวเปรียบเทียบความเท่าเทียม |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนอ่านอย่างเดียว |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | ตัวเปรียบเทียบความเท่าเทียมที่จะใช้สำหรับการเปรียบเทียบองค์ประกอบ |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## System::MemoryExtensions::CommonPrefixLength(const Span\<T\>\&, const Span\<T\>\&, const SharedPtr\<TEqualityComparer\>\&) ฟังก์ชัน

ค้นหาความยาวของคำนำร่วมระหว่างสองสแปนที่สามารถแก้ไขได้โดยใช้ตัวเปรียบเทียบความเท่าเทียมแบบกำหนดเอง

```cpp
template<typename T,typename TEqualityComparer> int32_t System::MemoryExtensions::CommonPrefixLength(const Span<T> &span, const Span<T> &other, const SharedPtr<TEqualityComparer> &comparer)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |
| TEqualityComparer | ประเภทของตัวเปรียบเทียบความเท่าเทียม |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้แรก |
| other | const [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่สอง |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TEqualityComparer\>\& | ตัวเปรียบเทียบความเท่าเทียมที่จะใช้สำหรับการเปรียบเทียบองค์ประกอบ |

### ค่าที่ส่งคืน

จำนวนขององค์ประกอบที่ตรงกันตั้งแต่ต้นของทั้งสองสแปน

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../system/sharedptr/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)