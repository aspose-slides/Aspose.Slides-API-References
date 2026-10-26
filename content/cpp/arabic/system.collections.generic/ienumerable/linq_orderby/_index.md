---
title: LINQ_OrderBy()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بترتيب عناصر تسلسل تصاعديًا وفقًا لقيم المفتاح المختارة بواسطة keySelector.
type: docs
weight: 209
url: /ar/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) طريقة

يقوم بترتيب عناصر تسلسل تصاعديًا وفقًا لقيم المفتاح المختارة بواسطة keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| keySelector | دالة لاستخراج مفتاح من عنصر. |

### القيمة المرجعة

IOrderedEnumerable التي يتم فرز عناصرها وفقًا لمفتاح

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) طريقة




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* فئة [Func](../../../system/func/)
* فئة [IEnumerable](../)
* مساحة الاسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)