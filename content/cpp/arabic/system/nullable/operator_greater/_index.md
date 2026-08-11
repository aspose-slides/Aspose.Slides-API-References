---
title: operator>()
second_title: مرجع API Aspose.Slides للغة C++
description: دائمًا يعيد false.
type: docs
weight: 157
url: /ar/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const طريقة

دائمًا يعيد false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة المحددة عن طريق تطبيق [operator>()](./) على هذه القيم.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة للمقارنة معها |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | مرجع ثابت إلى القيمة للمقارنة معها |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة المحددة، وإلا - false

## Nullable::operator>(const Nullable\<T1\>\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة التي يمثلها كائن [Nullable](../) المحدد عن طريق تطبيق [operator>()](./) على هذه القيم.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) للمقارنة معه |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مرجع ثابت إلى كائن [Nullable](../) للمقارنة معه |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة التي يمثلها كائن [Nullable](../) المحدد، وإلا - false

## انظر أيضًا

* الفئة [Nullable](../)
* الهيكل [IsNullable](../../isnullable/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)