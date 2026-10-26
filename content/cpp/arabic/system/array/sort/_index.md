---
title: Sort()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بترتيب العناصر في المصفوفة المحددة باستخدام المقارن الافتراضي.
type: docs
weight: 742
url: /ar/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) طريقة

يقوم بترتيب العناصر في المصفوفة المحددة باستخدام المقارن الافتراضي.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | مصفوفة الهدف |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) طريقة

يقوم بترتيب نطاق من العناصر في المصفوفة المحددة باستخدام المقارن الافتراضي.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | مصفوفة الهدف |
| startIndex | int | الفهرس الذي يحدد بداية نطاق العناصر التي سيتم ترتيبها |
| count | int | حجم النطاق الذي سيتم ترتيب عناصره |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) طريقة

يقوم بترتيب العناصر في المصفوفة المحددة باستخدام المقارن المحدد.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | مصفوفة الهدف |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | كائن IComparer<T> يُستخدم لمقارنة عناصر المصفوفة |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) طريقة

غير مُنفذ.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) طريقة

يقوم بترتيب العناصر في المصفوفة المحددة باستخدام المقارنة المحددة.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) طريقة

يقوم بترتيب مصفوفتين، إحداهما تحتوي على **المفاتيح** والأخرى على العناصر المقابلة، بناءً على قيم المصفوفة التي تحتوي على المفاتيح، حيث تُقارن العناصر باستخدام operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TKey | نوع العناصر في مصفوفة **المفاتيح** |
| TValue | نوع العناصر في مصفوفة **العناصر** |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) التي تحتوي على قيم المفاتيح |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) التي تحتوي على العناصر التي تم ربطها بقيم المفاتيح في مصفوفة **المفاتيح** |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) طريقة

يقوم بترتيب مصفوفتين، إحداهما تحتوي على **المفاتيح** والأخرى على العناصر المقابلة، بناءً على قيم المصفوفة التي تحتوي على المفاتيح، حيث تُقارن العناصر باستخدام المقارن الافتراضي.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TKey | نوع العناصر في مصفوفة **المفاتيح** |
| TValue | نوع العناصر في مصفوفة **العناصر** |

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) التي تحتوي على قيم المفاتيح |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) التي تحتوي على العناصر التي تم ربطها بقيم المفاتيح في مصفوفة **المفاتيح** |
| index | int | الفهرس الذي يحدد بداية النطاق الذي سيتم ترتيبه |
| length | int | عدد العناصر في النطاق الذي سيتم ترتيبه |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* طريقة [Type](../../object/type/)
* فئة [Array](../)
* فئة [IComparer](../../../system.collections.generic/icomparer/)
* فئة [Comparison](../../comparison/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)