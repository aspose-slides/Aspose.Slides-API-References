---
title: operator<()
second_title: مرجع API Aspose.Slides للغة C++
description: دائمًا تُعيد false.
type: docs
weight: 170
url: /ar/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const طريقة

دائمًا تُعيد false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أقل من القيمة المحددة بتطبيق [operator<()](./) على هذه القيم.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | نوع القيمة للمقارنة معها |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | إشارة ثابتة إلى القيمة للمقارنة معها |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أقل من القيمة المحددة، وإلا - false

## Nullable::operator<(const Nullable\<T1\>\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أقل من القيمة التي يمثلها الكائن [Nullable](../) المحدد بتطبيق [operator<()](./) على هذه القيم.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| T1 | النوع الأساسي للكائن [Nullable](../) للمقارنة معه |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | إشارة ثابتة إلى الكائن [Nullable](../) للمقارنة معه |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أقل من القيمة التي يمثلها الكائن [Nullable](../) المحدد، وإلا - false

## انظر أيضًا

* فئة [Nullable](../)
* بنية [IsNullable](../../isnullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)