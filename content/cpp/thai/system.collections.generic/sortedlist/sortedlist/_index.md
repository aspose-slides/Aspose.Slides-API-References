---
title: SortedList()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างรายการเปล่า
type: docs
weight: 1
url: /th/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() ตัวสร้าง


สร้างรายการเปล่า

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) ตัวสร้าง


สร้างรายการเปล่า

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) ที่จะใช้ |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) ตัวสร้าง


ตัวสร้างสำเนา

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) ที่จะคัดลอกข้อมูลจาก |

## SortedList::SortedList(const map_t\&) ตัวสร้าง


ตัวสร้างสำเนา

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Map ที่คัดลอกข้อมูลจาก |

## SortedList::SortedList(int) ตัวสร้าง


สร้างรายการเปล่า

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| capacity | int | จำนวนขององค์ประกอบที่ต้องการสำรอง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)