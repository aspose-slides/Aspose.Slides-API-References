---
title: CanCast()
second_title: مرجع API Aspose.Slides برای C++
description: امکان تبدیل را بررسی می‌کند.
type: docs
weight: 40
url: /fa/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

در صورتی که مقدار غیر nullptr پس از تبدیل برگردانده شود، true و در غیر این صورت false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

در صورتی که مقدار غیر nullptr پس از تبدیل برگردانده شود، true و در غیر این صورت false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

در صورتی که مقدار غیر nullptr پس از تبدیل برگردانده شود، true و در غیر این صورت false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

همیشه true برمی‌گرداند.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

در صورتی که مقدار غیر nullptr پس از تبدیل برگردانده شود، true و در غیر این صورت false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

همیشه true برمی‌گرداند.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

در صورتی که عملیات تبدیل با موفقیت انجام شود، true و در غیر این صورت false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) تابع

امکان تبدیل را بررسی می‌کند.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Source | نوع منبع. |
| Result | نوع نتیجه. |

### مقدار بازگشت

همیشه false برمی‌گرداند.

## موارد مرتبط

* ساختار [CastType](../casttype/)
* فضای نام [System::Collections::Generic::Details::CastRules](../)
* کتابخانه [Aspose.Slides](../../)