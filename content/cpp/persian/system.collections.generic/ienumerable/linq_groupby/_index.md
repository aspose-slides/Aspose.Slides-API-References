---
title: LINQ_GroupBy()
second_title: Aspose.Slides برای C++ مرجع API
description: عناصر یک توالی را گروه‌بندی می‌کند.
type: docs
weight: 287
url: /fa/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method

عناصر یک توالی را گروه‌بندی می‌کند.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Key | نوع کلیدی که توسط keyPredicate بازگردانده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | یک تابع برای استخراج کلید برای هر عنصر. |

### مقدار بازگشتی

یک [IEnumerable](../) که شامل یک توالی از اشیاء و یک کلید است

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method

عناصر یک توالی را گروه‌بندی می‌کند.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Key | نوع کلیدی که توسط keyPredicate بازگردانده می‌شود |
| Element | نوع عنصری که توسط elementSelector بازگردانده می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | یک تابع برای استخراج کلید برای هر عنصر. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | یک تابع برای استخراج مقدار کلید برای هر عنصر. |

### مقدار بازگشتی

یک [IEnumerable](../) که شامل یک توالی از اشیاء و یک کلید است

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IEnumerable](../)
* کلاس [IGrouping](../../../system.linq/igrouping/)
* کلاس [Func](../../../system/func/)
* فضای‌نام [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)