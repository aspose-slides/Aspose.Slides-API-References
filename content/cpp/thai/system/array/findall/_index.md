---
title: FindAll()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงข้อมูลทั้งหมดที่ตรงกับเงื่อนไขที่กำหนดโดยพรีดิเกตที่ระบุ
type: docs
weight: 664
url: /th/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) เมธอด

ดึงคืนทุกองค์ประกอบที่ตรงกับเงื่อนไขที่กำหนดโดยพรีดิกาตัวที่ระบุ

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) เพื่อค้นหาองค์ประกอบใน |
| match | [System::Predicate](../../predicate/)\<T\> | พรีดิกาที่กำหนดเงื่อนไขเพื่อจับคู่กับองค์ประกอบของอาเรย์ |

### ค่าที่ส่งคืน

[Array](../) ที่ประกอบด้วยทุกองค์ประกอบที่ตรงกับเงื่อนไขที่กำหนดโดยพรีดิกาตัวที่ระบุ, หากพบ; มิฉะนั้น, [Array](../) ที่ว่างเปล่า.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)