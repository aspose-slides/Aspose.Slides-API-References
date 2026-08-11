---
title: operator-()
second_title: Aspose.Slides لمرجع API للغة C++
description: يطرح القيم القابلة للإلغاء والقيم التي تشير إلى null.
type: docs
weight: 222
url: /ar/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const طريقة

يطرح القيم القابلة للإلغاء والقيم التي تشير إلى null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيمن، يجب أن يكون nullptr_t. |

### قيمة الإرجاع

كائن [Nullable](../) فارغ.

## Nullable::operator-(const T1\&) const طريقة

يطرح القيم القابلة للإلغاء والقيم غير القابلة للإلغاء.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيمن. |

### المعاملات

| معمل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | القيمة التي تُطرح. |

### قيمة الإرجاع

نتيجة الطرح.

## Nullable::operator-(const Nullable\<T1\>\&) const طريقة

يطرح القيم القابلة للإلغاء.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيمن. |

### المعاملات

| معمل | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | القيمة التي تُطرح. |

### قيمة الإرجاع

نتيجة الطرح.

## انظر أيضًا

* الفئة [Nullable](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)