---
title: Sort()
second_title: Aspose.Slides สำหรับ C++ - เอกสารอ้างอิง API
description: จัดเรียง Span ด้วยตัวเปรียบเทียบที่กำหนดเอง.
type: docs
weight: 339
url: /th/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) ฟังก์ชัน


จัดเรียง [Span](../../system/span/) ด้วยตัวเปรียบเทียบที่กำหนดเอง.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |
| TComparer | ประเภทของอ็อบเจ็กต์ comparer |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะจัดเรียง |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer ไปยังอ็อบเจ็กต์ comparer สำหรับการเปรียบเทียบองค์ประกอบ |

## System::MemoryExtensions::Sort(Span\<T\>\&) ฟังก์ชัน


จัดเรียง [Span](../../system/span/) โดยใช้การเปรียบเทียบเริ่มต้น.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | span ที่จะจัดเรียง |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) ฟังก์ชัน


จัดเรียงคู่คีย์-ค่าโดยใช้ตัวเปรียบเทียบที่กำหนดเอง (คีย์และค่าถูกเรียงพร้อมกัน)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |
| TComparer | ประเภทของอ็อบเจ็กต์ comparer |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span ของคีย์ที่ต้องจัดเรียง |
| values | [Span](../../system/span/)\<TValue\>\& | span ของค่าที่ต้องจัดเรียง (รักษาความสอดคล้องกับคีย์) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Smart pointer ไปยังอ็อบเจ็กต์ comparer สำหรับการเปรียบเทียบคีย์ |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) ฟังก์ชัน


จัดเรียงคู่คีย์-ค่าโดยใช้ delegate การเปรียบเทียบ.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span ของคีย์ที่ต้องจัดเรียง |
| values | [Span](../../system/span/)\<TValue\>\& | span ของค่าที่ต้องจัดเรียง |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) delegate สำหรับการเปรียบเทียบคีย์ |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) ฟังก์ชัน


จัดเรียงคู่คีย์-ค่าโดยใช้การเปรียบเทียบเริ่มต้น.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | span ของคีย์ที่ต้องจัดเรียง |
| values | [Span](../../system/span/)\<TValue\>\& | span ของค่าที่ต้องจัดเรียง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [Span](../../system/span/)
* คลาส [Comparison](../../system/comparison/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)