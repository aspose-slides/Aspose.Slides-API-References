---
title: Exchange()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يبدّل القيمة على المتغيّر: يخزّن القيمة الجديدة ويعيد القيمة التي كان المتغيّر يحملها مباشرةً قبل التخزين."
type: docs
weight: 66
url: /ar/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T&, T) طريقة

يبدل القيمة على المتغير: يخزن القيمة الجديدة ويعيد القيمة التي كان المتغير يحملها مباشرةً قبل التخزين.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المتغير. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location1 | T\& | مرجع المتغير لتغييره. |
| value | T | القيمة التي سيتم تخزينها. |

### قيمة الإرجاع

قيمة المتغير مباشرةً قبل تغييره.

## Interlocked::Exchange(T&, T) طريقة

يبدل القيمة على المتغير: يخزن القيمة الجديدة ويعيد القيمة التي كان المتغير يحملها مباشرةً قبل التخزين. غير مُطبق.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المتغير. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location1 | T\& | مرجع المتغير لتغييره. |
| value | T | القيمة التي سيتم تخزينها. |

### قيمة الإرجاع

قيمة المتغير مباشرةً قبل تغييره.

## انظر أيضًا

* الفئة [Interlocked](../)
* النطاق [System::Threading](../../)
* المكتبة [Aspose.Slides](../../../)