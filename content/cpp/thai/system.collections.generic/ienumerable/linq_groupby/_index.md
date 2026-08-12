---
title: LINQ_GroupBy()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จัดกลุ่มองค์ประกอบของลำดับ.
type: docs
weight: 287
url: /th/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) เมธอด


จัดกลุ่มองค์ประกอบของลำดับ.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Key | ประเภทของคีย์ที่คืนโดย keyPredicate |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | ฟังก์ชันเพื่อดึงคีย์สำหรับแต่ละองค์ประกอบ. |

### ค่าที่คืน

[IEnumerable](../) ที่บรรจุลำดับของอ็อบเจ็กต์และคีย์

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) เมธอด


จัดกลุ่มองค์ประกอบของลำดับ.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Key | ประเภทของคีย์ที่คืนโดย keyPredicate |
| Element | ประเภทของอีลีเมนต์ที่คืนโดย elementSelector |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | ฟังก์ชันเพื่อดึงคีย์สำหรับแต่ละองค์ประกอบ. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | ฟังก์ชันเพื่อดึงค่าคีย์สำหรับแต่ละองค์ประกอบ. |

### ค่าที่คืน

[IEnumerable](../) ที่บรรจุลำดับของอ็อบเจ็กต์และคีย์

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) เมธอด




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) เมธอด




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEnumerable](../)
* คลาส [IGrouping](../../../system.linq/igrouping/)
* คลาส [Func](../../../system/func/)
* เนมสเปซ [System::Collections::Generic](../../)
* ไลบรารี [Aspose.Slides](../../../)