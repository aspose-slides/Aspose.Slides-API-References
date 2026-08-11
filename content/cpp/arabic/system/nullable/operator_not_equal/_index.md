---
title: operator!=()
second_title: مرجع Aspose.Slides للـ C++ API
description: يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي ليست null.
type: docs
weight: 144
url: /ar/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const طريقة


يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي ليست null.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي ليست null، وإلا - خاطئ

## Nullable::operator!=(const T1\&) const طريقة


يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي ليست مساوية للقيمة المحددة.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع القيمة للمقارنة معها |

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | إشارة ثابتة إلى القيمة للمقارنة معها |

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي ليست مساوية للقيمة المحددة، وإلا - خاطئ

## Nullable::operator!=(const Nullable\<T1\>\&) const طريقة


يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي ليست مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | النوع الأساسي لكائن [Nullable](../) للمقارنة معه |

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | إشارة ثابتة إلى كائن [Nullable](../) للمقارنة معه |

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي ليست مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد، وإلا - خاطئ

## انظر أيضا

* الفئة [Nullable](../)
* الهيكل [IsNullable](../../isnullable/)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)