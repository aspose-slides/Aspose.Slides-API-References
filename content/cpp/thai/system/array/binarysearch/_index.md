---
title: BinarySearch()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการค้นหาแบบไบนารีในอาเรย์ที่เรียงลำดับแล้ว.
type: docs
weight: 612
url: /th/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) เมธอด

ทำการค้นหาแบบไบนารีในอาร์เรย์ที่เรียงลำดับแล้ว.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | อาเรย์ที่เรียงลำดับเพื่อทำการค้นหา |
| item | const T\& | รายการที่ต้องการค้นหา |

### ค่าที่ส่งคืน

[Index](../../index/) ของรายการที่ค้นพบหากพบ, มิฉะนั้น จะเป็นจำนวนเต็มลบที่เป็นคอมพลีเมนต์แบบบิตของดัชนีของรายการถัดไปที่มีค่ามากกว่ารายการที่ค้นหา หรือ หากไม่มีรายการที่มากกว่า คอมพลีเมนต์แบบบิตของจำนวนสมาชิกในอาเรย์.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Array](../)
* คลาส [IComparer](../../../system.collections.generic/icomparer/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)