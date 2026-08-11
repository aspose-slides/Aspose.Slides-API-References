---
title: Cast()
second_title: مرجع API Aspose.Slides برای C++
description: نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع و نوع نتیجه یکسان باشند.
type: docs
weight: 14
url: /fa/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع و نوع نتیجه یکسان باشند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع بتواند به‌صورت ایستا به نوع نتیجه تبدیل شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که انواع یکسان نیستند و نوع منبع نمی‌تواند به‌صورت ایستا به نوع نتیجه تبدیل شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع به‌صورت جعبه‌بندی به شیء کلاس [Nullable](../../system/nullable/) تبدیل می‌شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع از نمونهٔ کلاس [Nullable](../../system/nullable/) استخراج شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع به‌صورت جعبه‌بندی به شیء کلاس [Object](../../system/object/) تبدیل می‌شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که نوع منبع از نمونهٔ کلاس [Object](../../system/object/) استخراج شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## System::Collections::Generic::Details::CastRules::Cast(Source) تابع


نوع منبع را به نوع نتیجه تبدیل می‌کند. زمانی استفاده می‌شود که تبدیل نامعتبر باشد یا تبدیل به‌صورت صریح انجام شود.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### مقدار بازگشتی

The cast result.

## نگاه کنید به

* ساختار [CastType](../casttype/)
* فضای نام [System::Collections::Generic::Details::CastRules](../)
* کتابخانه [Aspose.Slides](../../)