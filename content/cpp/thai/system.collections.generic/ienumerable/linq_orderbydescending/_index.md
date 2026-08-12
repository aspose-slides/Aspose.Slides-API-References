---
title: LINQ_OrderByDescending()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จัดเรียงองค์ประกอบของลำดับในลำดับขาลงตามค่าคีย์ที่เลือกโดย keySelector.
type: docs
weight: 222
url: /th/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) method

จัดเรียงองค์ประกอบของลำดับในลำดับขาลงตามค่าคีย์ที่เลือกโดย keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| keySelector | ฟังก์ชันเพื่อดึงคีย์จากองค์ประกอบหนึ่ง. |

### ค่ารีเทิร์น

IOrderedEnumerable ที่มีองค์ประกอบถูกจัดเรียงในลำดับขาลงของคีย์

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) method

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* คลาส [Func](../../../system/func/)
* คลาส [IEnumerable](../)
* เนมสเปซ [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)