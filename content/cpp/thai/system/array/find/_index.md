---
title: Find()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ค้นหาตำแหน่งแรกในอาเรย์ที่ระบุซึ่งตรงตามเงื่อนไขของพรีดิเกตที่ระบุ
type: docs
weight: 651
url: /th/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) เมธอด

ค้นหาตำแหน่งแรกในอาเรย์ที่ระบุซึ่งตรงตามเงื่อนไขของพรีดิเกตที่ระบุ

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) เพื่อค้นหาตัวองค์ประกอบใน |
| match | [System::Predicate](../../predicate/)\<T\> | พรีดิเกตที่กำหนดเงื่อนไขสำหรับจับคู่กับองค์ประกอบของอาเรย์ |

### ค่าที่ส่งคืน

สำเนาขององค์ประกอบแรกในอาเรย์ที่ตรงตามเงื่อนไขที่กำหนดโดยพรีดิเกต, หากไม่พบจะคืนค่าเริ่มต้นของประเภท T

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)