---
title: begin()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: وصول إلى طريقة begin() لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصيص يحتوي على طريقة begin().
type: docs
weight: 378
url: /ar/system/smartptr/begin/
---
## SmartPtr::begin() طريقة

وصول إلى طريقة [begin()](./) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصيص يحتوي على طريقة [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### قيمة الإرجاع

مؤشر إلى بداية المجموعة

## SmartPtr::begin() const طريقة

وصول إلى طريقة [begin()](./) لمجموعة أساسية. يتم التجميع فقط إذا كان SmartPtr_ من نوع تخصيص يحتوي على طريقة [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### قيمة الإرجاع

مؤشر إلى بداية المجموعة

## انظر أيضًا

* الفئة [SmartPtr](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)