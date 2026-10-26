---
title: Dictionary()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ قاموسًا فارغًا.
type: docs
weight: 1
url: /ar/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() منشئ

ينشئ قاموسًا فارغًا.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Dictionary::Dictionary(const map_t\&) منشئ

ينسخ البيانات من الخريطة.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | الخريطة التي تُنسخ البيانات منها. |

## Dictionary::Dictionary(int) منشئ

الإصدار المتحمِّل الذي يتوافق مع إنشاء قاموس مُخصَّص مسبقًا؛ لا يُجري أي تخصيص فعليًا.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | السعة للتخصيص؛ تُتجاهل. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) منشئ

منشئ النسخ.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../) لنسخ البيانات منه. |

## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) منشئ

منشئ النسخ.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | قاموس المصدر. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) كائن لاستخدامه. |

## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) منشئ

ينشئ قاموسًا فارغًا.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) لاستخدامه. |

## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) منشئ

ينشئ قاموسًا فارغًا.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| capacity | int | [Dictionary](../) السعة بعد الإنشاء؛ تُتجاهل. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) لاستخدامه. |

## راجع أيضًا

* تعريف نوع [map_t](../map_t/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Dictionary](../)
* فئة [IDictionary](../../idictionary/)
* فئة [IEqualityComparer](../../iequalitycomparer/)
* النطاق [System::Collections::Generic](../../)
* المكتبة [Aspose.Slides](../../../)