---
title: LINQ_Max()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและส่งคืนค่ามากที่สุดที่ได้จากผลลัพธ์
type: docs
weight: 352
url: /th/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) เมธอด


เรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับทั่วไปและส่งกลับค่ามากที่สุดที่ได้จากการแปลง

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ResultType | ประเภทของค่าที่ถูกส่งกลับโดย selector. |

### พารามิเตอร์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | ฟังก์ชันแปลงที่ใช้กับแต่ละองค์ประกอบ. |

### ค่าที่ส่งกลับ

ค่ามากที่สุดในลำดับ.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) เมธอด




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## ดูเพิ่มเติม

* คลาส [Func](../../../system/func/)
* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)