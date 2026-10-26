---
title: Sort()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จัดเรียงองค์ประกอบในรายการ.
type: docs
weight: 521
url: /th/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) เมธอด

จัดเรียงองค์ประกอบในรายการ.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | ตัวเปรียบเทียบที่จะใช้. |

## List::Sort() เมธอด

จัดเรียงองค์ประกอบในรายการโดยใช้ตัวเปรียบเทียบเริ่มต้น.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) เมธอด

จัดเรียงองค์ประกอบในส่วนของรายการ.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นของส่วน. |
| count | int | ขนาดของส่วน. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | ตัวเปรียบเทียบที่จะใช้. |

## List::Sort(Comparison\<T\>, bool) เมธอด

จัดเรียงองค์ประกอบในรายการ.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) เพื่อใช้. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparer](../../icomparer/)
* Class [List](../)
* Class [Comparison](../../../system/comparison/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)