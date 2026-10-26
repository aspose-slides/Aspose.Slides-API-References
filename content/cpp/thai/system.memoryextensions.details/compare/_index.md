---
title: Compare()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบตัวชี้อัจฉริยะสองตัว
type: docs
weight: 1
url: /th/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) function

เปรียบเทียบตัวชี้อัจฉริยะสองตัว

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Type of first smart pointer |
| U | Type of second smart pointer |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | First smart pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Second smart pointer |

### ค่าที่ส่งกลับ

[Comparison](../../system/comparison/) ผลลัพธ์ (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) function

เปรียบเทียบค่าตัวเลขสองค่า

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Arithmetic type |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const T\& | First value |
| b | const T\& | Second value |

### ค่าที่ส่งกลับ

[Comparison](../../system/comparison/) ผลลัพธ์ (0 if equal, -1 if a < b, 1 if a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) function

เปรียบเทียบตัวชี้อัจฉริยะกับค่า

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | Type pointed to by smart pointer |
| U | Type of value |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart pointer |
| b | const U\& | Value |

### ค่าที่ส่งกลับ

[Comparison](../../system/comparison/) ผลลัพธ์ (0 if equal, -1 if a < b, 1 if a > b)

## ดูเพิ่มเติม

* กำหนดประเภท [SharedPtr](../../system/sharedptr/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)