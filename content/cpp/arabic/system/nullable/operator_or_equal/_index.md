---
title: operator|=()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يطبق operator|=() على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كقيمة على الجانب الأيمن.
type: docs
weight: 261
url: /ar/system/nullable/operator_or_equal/
---
## Nullable::operator|=(bool) الطريقة


يطبق [operator|=()](./) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كقيمة على الجانب الأيمن.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | معامل القالب لجعل SFINAE يعمل. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | **bool** | قيمة منطقية تُستخدم كقيمة على الجانب الأيمن للـ [operator|=()](./) المُطبَّق على القيمة التي يمثلها الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات.

## أنظر أيضًا

* الفئة [Nullable](../)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)