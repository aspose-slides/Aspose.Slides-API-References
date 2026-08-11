---
title: SortedDictionary()
second_title: مرجع API ل Aspose.Slides للغة C++
description: ينشئ قاموسًا فارغًا.
type: docs
weight: 14
url: /ar/system.collections.generic/sorteddictionary/sorteddictionary/
---
## SortedDictionary::SortedDictionary() منشئ

ينشئ قاموسًا فارغًا.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary()
```

## SortedDictionary::SortedDictionary(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) منشئ

ينشئ قاموسًا فارغًا.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) للاستخدام. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) منشئ

منشئ نسخة.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | القاموس المصدر لنسخ البيانات منه. |

## SortedDictionary::SortedDictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) منشئ

منشئ نسخة.

```cpp
System::Collections::Generic::SortedDictionary<TKey, TValue>::SortedDictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IComparer<typename BasePointerType<TKey>::type>> &comparer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | القاموس المصدر لنسخ البيانات منه. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\& | [Comparer](../../comparer/) للاستخدام. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [SortedDictionary](../)
* فئة [IComparer](../../icomparer/)
* فئة [IDictionary](../../idictionary/)
* مساحة الاسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)