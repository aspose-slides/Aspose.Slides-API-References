---
title: operator=()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يعين قيمة فارغة (null) إلى الكائن الحالي.
type: docs
weight: 14
url: /ar/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) طريقة

يقوم بتعيين قيمة فارغة (null) للكائن الحالي.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### قيمة الإرجاع

كائن [Nullable](../) يمثل قيمة فارغة.

## Nullable::operator=(const T1\&) طريقة

يستبدل القيمة الحالية الممثلة للكائن بالقيمة المحددة.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| The | نوع القيمة الجديدة التي سيتم تمثيلها بواسطة الكائن الحالي |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const T1\& | القيمة الجديدة التي سيتم تمثيلها بواسطة الكائن الحالي |

### قيمة الإرجاع

إشارة إلى الكائن نفسه

## Nullable::operator=(const Nullable\<T1\>\&) طريقة

يستبدل القيمة الحالية الممثلة للكائن بالقيمة المحددة.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| The | نوع القيمة الجديدة التي سيتم تمثيلها بواسطة الكائن الحالي |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | القيمة الجديدة التي سيتم تمثيلها بواسطة الكائن الحالي |

### قيمة الإرجاع

إشارة إلى الكائن نفسه

## انظر أيضًا

* الفئة [Nullable](../)
* الهيكل [IsNullable](../../isnullable/)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)