---
title: CompareExchange()
second_title: مرجع API ل Aspose.Slides للغة C++
description: "يقوم بتبادل القيمة على المتغيّر: يتحقق ما إذا كان المتغيّر يساوي قيمة محددة ويخزن القيمة الجديدة فقط إذا كانت القيمة المخزنة تطابق المتوقعة."
type: docs
weight: 79
url: /ar/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) طريقة


يقوم بتبادل القيمة على المتغيّر: يتحقق ما إذا كان المتغيّر يساوي قيمة محددة ويخزن القيمة الجديدة فقط إذا كانت القيمة المخزنة تطابق المتوقعة.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المتغيّر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location1 | T\& | مرجع المتغيّر لتغييره. |
| value | T | القيمة المراد تخزينها. |
| comparand | T | القيمة التي يُقارن بها قيمة المتغيّر قبل التبادل. |

### قيمة الإرجاع

قيمة المتغيّر عند بدء العملية بغض النظر عما إذا تم تغييره أم لا.

## Interlocked::CompareExchange(T\&, T, T) طريقة


يقوم بتبادل القيمة على المتغيّر: يتحقق ما إذا كان المتغيّر يساوي قيمة محددة ويخزن القيمة الجديدة فقط إذا كانت القيمة المخزنة تطابق المتوقعة. غير مُنفّذ.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع المتغيّر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location1 | T\& | مرجع المتغيّر لتغييره. |
| value | T | القيمة المراد تخزينها. |
| comparand | T | القيمة التي يُقارن بها قيمة المتغيّر قبل التبادل. |

### قيمة الإرجاع

قيمة المتغيّر عند بدء العملية بغض النظر عما إذا تم تغييره أم لا.

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) طريقة


يقوم بتبادل القيمة على المتغيّر: يتحقق ما إذا كان المتغيّر يساوي قيمة محددة ويخزن القيمة الجديدة فقط إذا كانت القيمة المخزنة تطابق المتوقعة.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location1 | **int32_t**\& | مرجع المتغيّر لتغييره. |
| value | **int32_t** | القيمة المراد تخزينها. |
| comparand | **int32_t** | القيمة التي يُقارن بها قيمة المتغيّر قبل التبادل. |
| succeeded | **bool**\& | إشارة إلى المتغيّر التي تُضبط إلى true إذا تم التبادل وإلى false خلاف ذلك. |

### قيمة الإرجاع

قيمة المتغيّر عند بدء العملية بغض النظر عما إذا تم تغييره أم لا.

## انظر أيضًا

* الفئة [Interlocked](../)
* المجال [System::Threading](../../)
* المكتبة [Aspose.Slides](../../../)