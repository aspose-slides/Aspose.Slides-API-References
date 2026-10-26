---
title: Cast()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحوِّل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يكون نوعا المصدر والنتيجة متماثلين.
type: docs
weight: 14
url: /ar/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يكون نوعا Source و Result متماثلين.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يمكن تحويل نوع Source إلى نوع Result ثابتًا.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما لا تكون الأنواع متماثلة ولا يمكن تحويل نوع Source إلى نوع Result ثابتًا.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يتم تغليف نوع Source إلى مثيل الفئة [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يتم فك تغليف نوع Source من مثيل الفئة [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يتم تغليف نوع Source إلى مثيل الفئة [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يتم فك تغليف نوع Source من مثيل الفئة [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## System::Collections::Generic::Details::CastRules::Cast(Source) function


يحوِّل نوع Source إلى نوع Result. يُستخدم عندما يكون التحويل غير صالح أو يكون التحويل صريحًا.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع Source. |
| Result | نوع Result. |

### قيمة الإرجاع

نتيجة التحويل.

## انظر أيضًا

* الهيكل [CastType](../casttype/)
* النطاق [System::Collections::Generic::Details::CastRules](../)
* المكتبة [Aspose.Slides](../../)