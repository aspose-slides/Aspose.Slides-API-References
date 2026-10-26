---
title: GetName()
second_title: مرجع API Aspose.Slides لـ C++
description: يرجع اسم الثابت التعددي الذي له القيمة المحددة.
type: docs
weight: 40
url: /ar/system/enum/getname/
---
## Enum::GetName(T) طريقة


يرجع اسم الثابت التعددي الذي له القيمة المحددة.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | T | قيمة الثابت التعددي الذي يجب إرجاع اسمه |

### قيمة الإرجاع

اسم الثابت التعددي المحدد

## انظر أيضاً

* تعريف نوع [UnderlyingType](../underlyingtype/)
* فئة [String](../../string/)
* بنية [Enum](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)