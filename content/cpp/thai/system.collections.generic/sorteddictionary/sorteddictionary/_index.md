---
title: SortedDictionary()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างพจนานุกรมว่าง.
type: docs
weight: 14
url: /th/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() คอนสตรัคเตอร์

สร้างพจนานุกรมว่าง.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) คอนสตรัคเตอร์

สร้างพจนานุกรมว่าง.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) เพื่อใช้. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | พจนานุกรมต้นทางเพื่อคัดลอกข้อมูลจาก. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | พจนานุกรมต้นทางเพื่อคัดลอกข้อมูลจาก. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) เพื่อใช้. |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SortedDictionary](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)