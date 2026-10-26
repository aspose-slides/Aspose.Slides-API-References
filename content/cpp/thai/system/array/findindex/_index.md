---
title: FindIndex()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาตัวอิลิเมนต์แรกในอาเรย์ที่ระบุที่ตรงกับเงื่อนไขของพรีดิเคตที่ระบุ
type: docs
weight: 638
url: /th/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) เมธอด

ค้นหาตัวอิลิเมนต์แรกในอาเรย์ที่ระบุที่ตรงกับเงื่อนไขของพรีดิเคตที่ระบุ

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) เพื่อค้นหาตัวอิลิเมนต์ใน |
| match | [System::Predicate](../../predicate/)\<T\> | พรีดิเคตที่กำหนดเงื่อนไขสำหรับจับคู่กับอิลิเมนต์ของอาเรย์ |

### ค่าที่คืนกลับ

ดัชนีของอิลิเมนต์แรกในอาเรย์ที่ตรงกับเงื่อนไขที่กำหนดโดยพรีดิเคต, หากไม่พบจะคืนค่า -1

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)