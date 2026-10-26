---
title: GetDescription()
second_title: مرجع API Aspose.Slides للـ C++
description: يعيد اسم ثابت التعداد الذي يملك القيمة المحددة.
type: docs
weight: 53
url: /ar/system/enum/getdescription/
---
## Enum::GetDescription(T) طريقة

يُرجع اسم ثابت التعداد الذي يملك القيمة المحددة.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### المعلمات

| معامل | النوع | الوصف |
| --- | --- | --- |
| value | T | قيمة ثابت التعداد الذي يجب إرجاع اسمه |

### قيمة الإرجاع

اسم ثابت التعداد المحدد

## راجع أيضًا

* Typedef [UnderlyingType](../underlyingtype/)
* فئة [String](../../string/)
* هيكل [Enum](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)