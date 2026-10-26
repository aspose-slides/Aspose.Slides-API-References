---
title: LINQ_ThenBy()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بأداء ترتيب لاحق للعناصر في تسلسل بترتيب تصاعدي وفقًا لمفتاح.
type: docs
weight: 27
url: /ar/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) طريقة

يقوم بترتيب لاحق للعناصر في تسلسل بترتيب تصاعدي وفقًا لمفتاح.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| Key | نوع المفتاح الذي تُعيده keySelector. |

### الوسائط

| معلمة | نوع | الوصف |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | دالة لاستخراج مفتاح من كل عنصر. |

### قيمة الإرجاع

[System::Linq::IOrderedEnumerable](../) التي يتم ترتيب عناصرها وفقًا لمفتاح.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) طريقة

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IOrderedEnumerable](../)
* فئة [Func](../../../system/func/)
* نطاق [System::Linq](../../)
* مكتبة [Aspose.Slides](../../../)