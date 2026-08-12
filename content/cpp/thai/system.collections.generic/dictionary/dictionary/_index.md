---
title: Dictionary()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างพจนานุกรมว่าง.
type: docs
weight: 1
url: /th/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() คอนสตรัคเตอร์

สร้างพจนานุกรมว่าง

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) คอนสตรัคเตอร์

คัดลอกข้อมูลจากแผนที่

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | แผนที่เพื่อคัดลอกข้อมูลจาก. |

## Dictionary::Dictionary(int) คอนสตรัคเตอร์

ฟังก์ชันโอเวอร์โหลดที่สอดคล้องกับการสร้างพจนานุกรมที่จัดสรรล่วงหน้า; ไม่ทำการจัดสรรจริง ๆ

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | ความจุที่จะจัดสรร; ไม่สนใจ. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) เพื่อคัดลอกข้อมูลจาก. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) คอนสตรัคเตอร์

คอนสตรัคเตอร์คัดลอก

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | พจนานุกรมต้นฉบับ. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) วัตถุที่จะใช้. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) คอนสตรัคเตอร์

สร้างพจนานุกรมว่าง

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) เพื่อใช้. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) คอนสตรัคเตอร์

สร้างพจนานุกรมว่าง

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) ความจุหลังการสร้าง; ไม่สนใจ. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) เพื่อใช้. |

## ดูเพิ่มเติม

* Typedef [map_t](../map_t/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Dictionary](../)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)