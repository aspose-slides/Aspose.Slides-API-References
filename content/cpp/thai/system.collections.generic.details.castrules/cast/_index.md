---
title: Cast()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงประเภทต้นทางเป็นประเภทผลลัพธ์. ใช้เมื่อประเภทต้นทางและประเภทผลลัพธ์เป็นแบบเดียวกัน.
type: docs
weight: 14
url: /th/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางและประเภทผลลัพธ์เป็นเดียวกัน

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางสามารถแปลงแบบสถิตเป็นประเภทผลลัพธ์ได้

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทไม่เหมือนกันและประเภทต้นทางไม่สามารถแปลงแบบสถิตเป็นประเภทผลลัพธ์ได้

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางถูกบรรจุเป็นอินสแตนซ์ของคลาส [Nullable](../../system/nullable/)

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางถูกถอดบรรจุจากอินสแตนซ์ของคลาส [Nullable](../../system/nullable/)

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางถูกบรรจุเป็นอินสแตนซ์ของคลาส [Object](../../system/object/)

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต้นทางถูกถอดบรรจุจากอินสแตนซ์ของคลาส [Object](../../system/object/)

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## System::Collections::Generic::Details::CastRules::Cast(Source) ฟังก์ชัน


แปลงประเภทต้นทางเป็นประเภทผลลัพธ์ ใช้เมื่อการแปลงประเภทไม่ถูกต้องหรือการแปลงเป็นแบบชัดเจน

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทาง |
| Result | ประเภทผลลัพธ์ |

### ค่าที่ส่งกลับ

ผลลัพธ์ของการแปลงประเภท

## ดูเพิ่มเติม

* โครงสร้าง [CastType](../casttype/)
* เนมสเปซ [System::Collections::Generic::Details::CastRules](../)
* ไลบรารี [Aspose.Slides](../../)