---
title: operator>=()
second_title: Aspose.Slides لـ C++ مرجع API
description: دائمًا ما يُعيد false.
type: docs
weight: 183
url: /ar/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const طريقة

دائمًا ما يُعيد false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### قيمة الإرجاع

دائمًا - false

## Nullable::operator>=(const T1\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها الكائن المحدد من خلال تطبيق [operator>=()](./) على هاتين القيمتين.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | النوع الأساسي للقيمة للمقارنة مع القيمة التي يمثلها الكائن الحالي |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | مرجع ثابت إلى كائن للمقارنة مع الكائن الحالي |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها الكائن المحدد، وإلا - false

## Nullable::operator>=(const Nullable\<T1\>\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها كائن [Nullable](../) المحدد من خلال تطبيق [operator>=()](./) على هاتين القيمتين.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) للمقارنة معه |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | مرجع ثابت إلى كائن [Nullable](../) للمقارنة معه |

### قيمة الإرجاع

True إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها كائن [Nullable](../) المحدد، وإلا - false

## انظر أيضًا

* فئة [Nullable](../)
* هيكل [IsNullable](../../isnullable/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)