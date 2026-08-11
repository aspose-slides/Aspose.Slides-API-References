---
title: operator-=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع كائنًا من الفئة Nullable يمثل قيمة خالية.
type: docs
weight: 248
url: /ar/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) طريقة

إرجاع كائن من الفئة [Nullable](../) الذي يمثل قيمة خالية.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) طريقة

تطبق [operator-=()](./) على القيمة الممثلة بواسطة الكائن الحالي باستخدام القيمة المحددة كمعامل الجانب الأيمن.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة المستخدمة كقيمة الجانب الأيمن لـ [operator-=()](./) |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | مرجع ثابت إلى القيمة التي تُستخدم كقيمة الجانب الأيمن للـ [operator-=()](./) المُطبق على القيمة الممثلة بواسطة الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات

## Nullable::operator-=(const Nullable\<T1\>\&) طريقة

تطبق [operator-=()](./) على القيمة الممثلة بواسطة الكائن الحالي باستخدام القيمة الممثلة بواسطة الكائن [Nullable](../) المحدد كمعامل الجانب الأيمن.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) الذي تُستخدم قيمته كمعامل الجانب الأيمن لـ [operator-=()](./) |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مرجع ثابت إلى كائن [Nullable](../) الذي تُستخدم قيمته كمعامل الجانب الأيمن للـ [operator-=()](./) المُطبق على القيمة الممثلة بواسطة الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات

## انظر أيضًا

* فئة [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)