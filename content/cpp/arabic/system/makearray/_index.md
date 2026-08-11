---
title: MakeArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: دالة مصنع تُنشئ كائن Array جديد، وتملأه بالعناصر من قائمة التهيئة المحددة وتُعيد مؤشرًا ذكيًا يُشير إلى كائن Array.
type: docs
weight: 2029
url: /ar/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) دالة

دالة مصنع تُنشئ كائنًا جديدًا من نوع [Array](../array/)، وتملأه بالعناصر من قائمة التهيئة المحددة وتُعيد مؤشرًا ذكيًا يُشير إلى كائن [Array](../array/).

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| init | std::initializer_list\<T\> | The initialization list containing the elements to fill the array with |

### قيمة الإرجاع

مؤشر ذكي يُشير إلى الكائن [Array](../array/) المنشأ

## System::MakeArray(Args\&&...) دالة

دالة مصنع تُنشئ كائنًا جديدًا من نوع [Array](../array/) بتمرير المعاملات المحددة إلى مُنشئه.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### قيمة الإرجاع

مؤشر ذكي يُشير إلى الكائن [Array](../array/) المنشأ

## System::MakeArray(Integral, Args\&&...) دالة

دالة مصنع تُنشئ كائنًا جديدًا من نوع [Array](../array/) بتمرير المعاملات المحددة إلى مُنشئه.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |
| Integral | Type of array size. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| size | Integral | Size of the array being created. |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### قيمة الإرجاع

مؤشر ذكي يُشير إلى الكائن [Array](../array/) المنشأ

## انظر أيضًا

* تعريف نوع [ArrayPtr](../arrayptr/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)