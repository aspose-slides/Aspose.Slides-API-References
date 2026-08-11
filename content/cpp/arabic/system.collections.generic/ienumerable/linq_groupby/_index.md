---
title: LINQ_GroupBy()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتجميع عناصر تسلسل.
type: docs
weight: 287
url: /ar/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) طريقة


يقوم بتجميع عناصر تسلسل.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Key | نوع المفتاح الذي تُعيده الدالة keyPredicate |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | دالة لاستخراج المفتاح لكل عنصر. |

### قيمة الإرجاع

An [IEnumerable](../) that contains a sequence of objects and a key

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) طريقة


يقوم بتجميع عناصر تسلسل.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Key | نوع المفتاح الذي تُعيده الدالة keyPredicate |
| Element | نوع العنصر الذي تُعيده الدالة elementSelector |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | دالة لاستخراج المفتاح لكل عنصر. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | دالة لاستخراج قيمة المفتاح لكل عنصر. |

### قيمة الإرجاع

An [IEnumerable](../) that contains a sequence of objects and a key

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) طريقة




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) طريقة




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IEnumerable](../)
* فئة [IGrouping](../../../system.linq/igrouping/)
* فئة [Func](../../../system/func/)
* مساحة الاسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)