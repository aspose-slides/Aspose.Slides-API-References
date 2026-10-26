---
title: Compare()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบสองค่า.
type: docs
weight: 2731
url: /th/system/compare/
---
## System::Compare(const TA\&, const TB\&) ฟังก์ชัน


เปรียบเทียบสองค่า

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TA | ประเภทของตัวเปรียบเทียบแรก |
| TB | ประเภทของตัวเปรียบเทียบที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const TA\& | ตัวเปรียบเทียบแรก |
| b | const TB\& | ตัวเปรียบเทียบที่สอง |

### ค่าที่ส่งกลับ

- 1 หาก **a** มีค่าต่ำกว่า **b**; 0 หากค่าทั้งสองเท่ากัน; 1 หาก **a** มีค่ามากกว่า **b**


## System::Compare(const TA\&, const TB\&) ฟังก์ชัน


เปรียบเทียบสองค่าจุดลอยตัว

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TA | ประเภทของตัวเปรียบเทียบแรก |
| TB | ประเภทของตัวเปรียบเทียบที่สอง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const TA\& | ตัวเปรียบเทียบแรก |
| b | const TB\& | ตัวเปรียบเทียบที่สอง |

### ค่าที่ส่งกลับ

- 1 หาก **a** มีค่าต่ำกว่า **b**; 0 หากค่าทั้งสองเท่ากัน; 1 หาก **a** มีค่ามากกว่า **b**


## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)