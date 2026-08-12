---
title: TrueForAll()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดว่าทุกองค์ประกอบในอาร์เรย์ที่ระบุตรงตามเงื่อนไขที่กำหนดโดยพรีดิเคทที่ระบุ
type: docs
weight: 677
url: /th/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) เมธอด

กำหนดว่าทุกองค์ประกอบในอาร์เรย์ที่ระบุตรงตามเงื่อนไขที่กำหนดโดยพรีดิเคทที่ระบุหรือไม่.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) องค์ประกอบที่ต้องตรวจสอบกับเงื่อนไข |
| match | [System::Predicate](../../predicate/)\<T\> | พรีดิเคทที่กำหนดเงื่อนไขเพื่อให้ตรงกับองค์ประกอบของอาร์เรย์ |

### ค่าที่ส่งคืน

true หากทุกองค์ประกอบของอาร์เรย์ arr ตรงตามเงื่อนไขที่กำหนดโดยพรีดิเคท match, มิฉะนั้น false

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)