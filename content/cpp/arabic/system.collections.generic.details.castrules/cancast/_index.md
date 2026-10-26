---
title: CanCast()
second_title: مرجع Aspose.Slides للـ C++ API
description: يفحص إمكانية التحويل.
type: docs
weight: 40
url: /ar/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

صحيح عندما تُرجع قيمة غير nullptr بعد التحويل، وإلا خطأ.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

صحيح عندما تُرجع قيمة غير nullptr بعد التحويل، وإلا خطأ.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

صحيح عندما تُرجع قيمة غير nullptr بعد التحويل، وإلا خطأ.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

دائمًا ما تُرجع صحيح.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

صحيح عندما تُرجع قيمة غير nullptr بعد التحويل، وإلا خطأ.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

دائمًا ما تُرجع صحيح.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

صحيح إذا تم تنفيذ عملية التحويل بنجاح، وإلا خطأ.

## System::Collections::Generic::Details::CastRules::CanCast(Source) دالة

يفحص إمكانية التحويل.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### معاملات القالب

| معامل | الوصف |
| --- | --- |
| Source | نوع المصدر. |
| Result | نوع النتيجة. |

### قيمة الإرجاع

دائمًا ما تُرجع خطأ.

## انظر أيضا

* بنية [CastType](../casttype/)
* مساحة اسم [System::Collections::Generic::Details::CastRules](../)
* مكتبة [Aspose.Slides](../../)