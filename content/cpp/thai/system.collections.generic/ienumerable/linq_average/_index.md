---
title: LINQ_Average()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข.
type: docs
weight: 365
url: /th/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() เมธอด

คำนวณค่าเฉลี่ยของลำดับของค่าตัวเลข

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### ค่าที่ส่งกลับ

ค่าเฉลี่ยของค่าภายในลำดับ

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) เมธอด

คำนวณค่าเฉลี่ยของลำดับของค่าที่ได้จากการเรียกใช้ฟังก์ชันแปลงบนแต่ละองค์ประกอบของลำดับอินพุต

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ResultType | ประเภทของค่าที่ส่งกลับโดย selector. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | ฟังก์ชันแปลงที่จะนำไปใช้กับแต่ละองค์ประกอบ. |

### ค่าที่ส่งกลับ

ค่าเฉลี่ยของค่าที่ได้จากการฉาย

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) เมธอด



```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## ดูเพิ่มเติม

* คลาส [IEnumerable](../)
* คลาส [Func](../../../system/func/)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)