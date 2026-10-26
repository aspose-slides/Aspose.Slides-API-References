---
title: Nullable()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: ينشئ كائنًا يمثل قيمة فارغة.
type: docs
weight: 1
url: /ar/system/nullable/nullable/
---
## Nullable::Nullable() منشئ

ينشئ كائنًا يمثل قيمة فارغة.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) منشئ

ينشئ كائنًا يمثل null.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) منشئ

ينشئ كائنًا من الفئة [Nullable](../) يمثل القيمة المحددة التي تم تحويلها (إذا لزم الأمر) إلى قيمة النوع الأساسي T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة المحددة |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const T1\& | إشارة ثابتة إلى القيمة التي سيُمثَّلها الكائن [Nullable](../) الذي تم إنشاؤه حديثًا |

## Nullable::Nullable(const Nullable\<T1\>\&) منشئ

ينشئ كائنًا يمثل قيمة يتم تمثيلها بواسطة الكائن [Nullable](../) المحدد. قد يمثل الكائن القابل للفراغ قيمة من نوع مختلف عن النوع الأساسي للكائن المُنشأ، وفي هذه الحالة تُحوَّل القيمة المُمثلة إلى قيمة من النوع T.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع القيمة التي يمثلها الكائن [Nullable](../) المحدد |

## انظر أيضًا

* الفئة [Nullable](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)