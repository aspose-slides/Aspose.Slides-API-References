---
title: operator&=()
second_title: Aspose.Slides لمرجع API للغة C++
description: يطبق operator&=() على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل على الجانب الأيمن.
type: docs
weight: 274
url: /ar/system/nullable/operator_and_equal/
---
## Nullable::operator&=(bool) طريقة


يطبق [operator&=()](./) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل على الجانب الأيمن.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | معامل القالب لجعل SFINAE يعمل. |

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| other | **bool** | قيمة منطقية تُستخدم كقيمة على الجانب الأيمن من [operator&=()](./) المطبقة على القيمة التي يمثلها الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات.

## انظر أيضًا

* فئة [Nullable](../)
* مساحة الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)