---
title: operator+=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد تعيين الكائن الحالي بحيث يمثل قيمة فارغة.
type: docs
weight: 235
url: /ar/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) طريقة

يعيد تعيين الكائن الحالي بحيث يمثل قيمة فارغة.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### قيمة الإرجاع

نسخة من الذات

## Nullable::operator+=(const T1\&) طريقة

يطبق [operator+=()](./) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كوسيط على الجانب الأيمن.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع القيمة المستخدمة كقيمة على الجانب الأيمن لـ [operator+=()](./) |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | مرجع ثابت إلى القيمة التي تُستخدم كقيمة على الجانب الأيمن للـ [operator+=()](./) المطبقة على القيمة التي يمثلها الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات

## Nullable::operator+=(const Nullable\<T1\>\&) طريقة

يطبق [operator+=()](./) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة التي يمثلها كائن [Nullable](../) المحدد كوسيط على الجانب الأيمن.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) التي تُستخدم قيمته كوسيط على الجانب الأيمن للـ [operator+=()](./) |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مرجع ثابت إلى كائن [Nullable](../) التي تُستخدم قيمته كوسيط على الجانب الأيمن للـ [operator+=()](./) المطبق على القيمة التي يمثلها الكائن الحالي. |

### قيمة الإرجاع

مرجع إلى الذات

## انظر أيضًا

* الفئة [Nullable](../)
* الهيكل [IsNullable](../../isnullable/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)