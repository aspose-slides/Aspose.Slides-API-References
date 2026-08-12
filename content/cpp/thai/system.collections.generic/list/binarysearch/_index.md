---
title: BinarySearch()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ค้นหารายการในรายการที่เรียงลำดับ.
type: docs
weight: 339
url: /th/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const เมธอด

ค้นหารายการในรายการที่เรียงลำดับ.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | const T\& | รายการที่ต้องการค้นหา. |

### ค่าที่ส่งกลับ

[Index](../../../system/index/) ของรายการในรายการที่เรียงลำดับหรือคอมพลีเมนต์ของดัชนีที่ใกล้ที่สุด.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const เมธอด

ค้นหารายการในรายการที่เรียงลำดับ.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | const T\& | รายการที่ต้องการค้นหา. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) ที่ใช้. |

### ค่าที่ส่งกลับ

[Index](../../../system/index/) ของรายการในรายการที่เรียงลำดับหรือคอมพลีเมนต์ของดัชนีที่ใกล้ที่สุด.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const เมธอด

ค้นหารายการในรายการที่เรียงลำดับ.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) ที่จุดเริ่มต้น. |
| count | int | [Range](../../../system/range/) ขนาด. |
| item | const T\& | รายการที่ต้องการค้นหา. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) ที่ใช้. |

### ค่าที่ส่งกลับ

[Index](../../../system/index/) ของรายการในรายการที่เรียงลำดับหรือคอมพลีเมนต์ของดัชนีที่ใกล้ที่สุด.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../)
* Class [IComparer](../../icomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)