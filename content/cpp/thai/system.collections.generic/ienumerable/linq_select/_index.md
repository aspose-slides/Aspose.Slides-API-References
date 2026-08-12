---
title: LINQ_Select()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงองค์ประกอบของลำดับ.
type: docs
weight: 248
url: /th/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) เมธอด

แปลงองค์ประกอบของลำดับ

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ResultType | ประเภทของค่าที่ส่งคืนโดย **selector**. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | ฟังก์ชันการแปลง. |

### ค่าที่ส่งกลับ

[IEnumerable](../) ที่มีองค์ประกอบที่ส่งคืนโดยฟังก์ชัน **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) เมธอด

แปลงแต่ละองค์ประกอบของลำดับเป็นรูปแบบใหม่โดยรวมดัชนีขององค์ประกอบ

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```

### พารามิเตอร์ต้นแบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ResultType | ประเภทของค่าที่ส่งคืนโดย **selector**. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | ฟังก์ชันการแปลง. |

### ค่าที่ส่งกลับ

[IEnumerable](../) ที่มีองค์ประกอบที่ส่งคืนโดยฟังก์ชัน **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) เมธอด

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) เมธอด

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEnumerable](../)
* คลาส [Func](../../../system/func/)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)