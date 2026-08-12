---
title: SortedSet()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างชุดเปล่า.
type: docs
weight: 1
url: /th/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() คอนสตรัคเตอร์


สร้างชุดเปล่า.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) คอนสตรัคเตอร์


สร้างชุดเปล่าที่มีความจุตามที่ระบุ.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) คอนสตรัคเตอร์


สร้างชุดเปล่าที่ใช้ตัวเปรียบเทียบความเท่าเทียมตามที่ระบุ.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) อ็อบเจกต์ที่เชื่อมโยงกับ [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) คอนสตรัคเตอร์


สร้าง [SortedSet](../) ตามค่าที่สามารถวนซ้ำได้.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedSet](../)
* Class [IComparer](../../icomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)