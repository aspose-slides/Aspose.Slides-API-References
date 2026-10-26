---
title: LINQ_SelectMany()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการแปลงแต่ละองค์ประกอบของลำดับและผสานลำดับที่ได้เป็นลำดับเดียว
type: docs
weight: 300
url: /th/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

Projects each element of a sequence and combines the resulting sequences into one sequence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| ResultType | ประเภทของค่าที่ส่งกลับโดย **selector**. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | ฟังก์ชันการแปลง. |

### ค่าที่ส่งกลับ

อ็อบเจ็กต์ [IEnumerable](../) ที่บรรจุผลลัพธ์ของการเรียกฟังก์ชันการฉายแบบหนึ่งต่อหลายบนแต่ละองค์ประกอบของลำดับอินพุต.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEnumerable](../)
* คลาส [Func](../../../system/func/)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)