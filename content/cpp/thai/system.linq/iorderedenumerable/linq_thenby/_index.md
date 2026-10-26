---
title: LINQ_ThenBy()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ทำการจัดเรียงต่อไปขององค์ประกอบในลำดับแบบเพิ่มขึ้นตามคีย์.
type: docs
weight: 27
url: /th/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) เมธอด

ทำการจัดเรียงต่อไปขององค์ประกอบในลำดับแบบเพิ่มขึ้นตามคีย์

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Key | ประเภทของคีย์ที่คืนโดย keySelector. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | ฟังก์ชันเพื่อดึงคีย์จากแต่ละองค์ประกอบ. |

### ค่าที่ส่งคืน

[System::Linq::IOrderedEnumerable](../) ซึ่งองค์ประกอบถูกจัดเรียงตามคีย์.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) เมธอด

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)