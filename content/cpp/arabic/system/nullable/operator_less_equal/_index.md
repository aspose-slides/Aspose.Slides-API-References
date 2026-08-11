---
title: operator<=()
second_title: مرجع API Aspose.Slides للغة C++
description: دائمًا تُعيد false.
type: docs
weight: 196
url: /ar/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const طريقة

دائمًا تُعيد false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة المحددة عن طريق تطبيق [operator<=()](./) على هذه القيم.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع القيمة للمقارنة معها |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | إشارة ثابتة إلى القيمة للمقارنة معها |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة المحددة، وإلا - false

## Nullable::operator<=(const Nullable\<T1\>\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد عن طريق تطبيق [operator<=()](./) على هذه القيم.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) للمقارنة معه |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | إشارة ثابتة إلى كائن [Nullable](../) للمقارنة معه |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد، وإلا - false

## انظر أيضًا

* فئة [Nullable](../)
* بنية [IsNullable](../../isnullable/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)