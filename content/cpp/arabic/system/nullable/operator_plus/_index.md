---
title: operator+()
second_title: مرجع Aspose.Slides للغة C++
description: يرجع نسخة مُنشأة بشكل افتراضي من فئة Nullable<T>.
type: docs
weight: 209
url: /ar/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const طريقة

يرجع نسخة مُنشأة بشكل افتراضي من فئة Nullable<T>.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const طريقة

يجمع القيم القابلة للـ null وغير القابلة للـ null.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيمن. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | القيمة للإضافة. |

### قيمة الإرجاع

نتيجة الجمع.

## Nullable::operator+(const Nullable\<T1\>\&) const طريقة

يجمع القيم القابلة للـ null.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع المعامل الأيمن. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | القيمة للإضافة. |

### قيمة الإرجاع

نتيجة الجمع.

## انظر أيضًا

* فئة [Nullable](../)
* مساحة أسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)