---
title: LINQ_Min()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ต่ำที่สุดที่ได้จากการแปลง
type: docs
weight: 339
url: /th/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) เมธอด

เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและคืนค่าที่ต่ำที่สุดที่ได้จากการแปลง

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ResultType | ประเภทของค่าที่ selector คืนกลับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | ฟังก์ชันแปลงที่จะใช้กับแต่ละองค์ประกอบ |

### ค่าที่ส่งคืน

ค่าที่ต่ำที่สุดในลำดับ

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) เมธอด

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## ดูเพิ่มเติม

* คลาส [Func](../../../system/func/)
* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)