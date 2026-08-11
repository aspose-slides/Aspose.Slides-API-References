---
title: operator==()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي هي null.
type: docs
weight: 118
url: /ar/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const طريقة

Determines if the value represented by the current object is null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي null، وإلا - خطأ

## Nullable::operator==(const T1\&) const طريقة

Determines if the value represented by the current object is equal to the specified value.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | نوع القيمة التي يتم المقارنة بها |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | مرجع ثابت إلى القيمة التي يتم المقارنة بها |

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة المحددة، وإلا - خطأ

## Nullable::operator==(const Nullable\<T1\>\&) const طريقة


Determines if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) للمقارنة به |

### الوسائط

| معامل | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مرجع ثابت إلى كائن [Nullable](../) للمقارنة به |

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد، وإلا - خطأ

## انظر أيضًا

* الفئة [Nullable](../)
* بنية [IsNullable](../../isnullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)