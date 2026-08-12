---
title: HashSet()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ข้อมูล RTTI.
type: docs
weight: 1
url: /th/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() constructor


ข้อมูล RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Remarks


สร้างชุดว่าง. 
## HashSet::HashSet(int) constructor


สร้างชุดว่างโดยกำหนดความจุ.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) constructor


สร้างชุดว่างที่ใช้ตัวเปรียบเทียบความเท่าเทียมที่ระบุ.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) อ็อบเจ็กต์สำหรับเชื่อมโยงกับ hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) constructor


สร้าง hashset จากค่า enumerable.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashSet](../)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)