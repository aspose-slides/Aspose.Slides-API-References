---
title: Sort()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เรียงลำดับองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบเริ่มต้น.
type: docs
weight: 742
url: /th/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) เมธอด

เรียงลำดับองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบเริ่มต้น.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | อาร์เรย์เป้าหมาย |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) เมธอด

เรียงลำดับช่วงขององค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบเริ่มต้น.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | อาร์เรย์เป้าหมาย |
| startIndex | int | ดัชนีที่ระบุจุดเริ่มต้นของช่วงขององค์ประกอบที่จะเรียงลำดับ |
| count | int | ขนาดของช่วงขององค์ประกอบที่จะเรียงลำดับ |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) เมธอด

เรียงลำดับองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้ตัวเปรียบเทียบที่กำหนด.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | อาร์เรย์เป้าหมาย |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | อ็อบเจ็กต์ IComparer<T> ที่ใช้เพื่อเปรียบเทียบองค์ประกอบของอาร์เรย์ |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) เมธอด

ยังไม่ได้ดำเนินการ.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) เมธอด

เรียงลำดับองค์ประกอบในอาร์เรย์ที่ระบุโดยใช้การเปรียบเทียบที่กำหนด.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) เมธอด

เรียงลำดับอาร์เรย์สองอาร์เรย์ หนึ่งอาร์เรย์ที่มีคีย์และอีกอาร์เรย์ที่มีรายการที่สอดคล้องกัน โดยอิงจากค่าของอาร์เรย์ที่มีคีย์ ซึ่งองค์ประกอบจะถูกเปรียบเทียบโดยใช้ตัวดำเนินการ <.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทขององค์ประกอบในอาร์เรย์ **keys** |
| TValue | ประเภทขององค์ประกอบในอาร์เรย์ **items** |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) ที่มีค่ากุญแจ |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) ที่มีรายการที่แมปกับค่ากุญแจในอาร์เรย์ **keys** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) เมธอด

เรียงลำดับอาร์เรย์สองอาร์เรย์ หนึ่งอาร์เรย์ที่มีคีย์และอีกอาร์เรย์ที่มีรายการที่สอดคล้องกัน โดยอิงจากค่าของอาร์เรย์ที่มีคีย์ ซึ่งองค์ประกอบจะถูกเปรียบเทียบโดยใช้ตัวเปรียบเทียบเริ่มต้น.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทขององค์ประกอบในอาร์เรย์ **keys** |
| TValue | ประเภทขององค์ประกอบในอาร์เรย์ **items** |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) ที่มีค่ากุญแจ |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) ที่มีรายการที่แมปกับค่ากุญแจในอาร์เรย์ **keys** |
| index | int | ดัชนีที่ระบุจุดเริ่มต้นของช่วงที่จะเรียงลำดับ |
| length | int | จำนวนขององค์ประกอบในช่วงที่จะเรียงลำดับ |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)