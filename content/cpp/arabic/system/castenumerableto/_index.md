---
title: CastEnumerableTo()
second_title: مرجع API لـ Aspose.Slides بلغة C++
description: يقوم بالتحويل الصريح لعناصر الكائن القابل للعد المحدد إلى نوع مختلف.
type: docs
weight: 2965
url: /ar/system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) دالة

يؤدي التحويل الصريح للعناصر في الكائن القابل للعد المحدد إلى نوع مختلف.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| To | النوع الذي سيتم تحويل العناصر من الكائن القابل للعد إليه بشكل ثابت |
| From | نوع الكائن القابل للعد |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| enumerable | const From\& | كائن قابل للعد يحتوي على العناصر التي سيتم تحويلها |

### قيمة الإرجاع

مؤشر إلى مجموعة جديدة تحتوي على عناصر من النوع **To** مكافئة لعناصر **enumerable**


## System::CastEnumerableTo(const From\&) دالة

يؤدي التحويل الصريح للعناصر في الكائن القابل للعد المحدد إلى نوع مختلف.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| To | النوع الذي سيتم تحويل العناصر من الكائن القابل للعد إليه بشكل ثابت |
| From | نوع الكائن القابل للعد |

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| enumerable | const From\& | هو مشتق من كائن Enumerable مع طريقة get_Count معرفة ويحتوي على العناصر التي سيتم تحويلها |

### قيمة الإرجاع

مؤشر إلى مجموعة جديدة تحتوي على عناصر من النوع **To** مكافئة لعناصر **enumerable**

## انظر أيضا

* الفئة [ListPtr](../../system.collections.generic/listptr/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)