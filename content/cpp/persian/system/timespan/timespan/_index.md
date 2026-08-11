---
title: TimeSpan()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء TimeSpan می‌سازد که بازهٔ زمانی صفر را نشان می‌دهد.
type: docs
weight: 1
url: /fa/system/timespan/timespan/
---
## TimeSpan::TimeSpan() سازنده

یک شیء [TimeSpan](../) می‌سازد که بازهٔ زمانی صفر را نشان می‌دهد.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) سازنده

یک نمونه از کلاس [TimeSpan](../) می‌سازد که بازهٔ زمانی مشخص شده را نشان می‌دهد.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود، به‌صورت تعداد فواصل ۱۰۰ نانوثانیه‌ای. |

## TimeSpan::TimeSpan(int, int, int) سازنده

یک نمونه از کلاس [TimeSpan](../) می‌سازد که بازهٔ زمانی را نمایان می‌سازد که برابر با مجموع تعداد ساعت‌ها، دقیقه‌ها و ثانیه‌های مشخص‌شده است.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| hours | int | تعداد ساعت‌ها در بخش ساعت‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| minutes | int | تعداد دقیقه‌ها در بخش دقیقه‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| seconds | int | تعداد ثانیه‌ها در بخش ثانیه‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |

## TimeSpan::TimeSpan(int, int, int, int, int) سازنده

یک نمونه از کلاس [TimeSpan](../) می‌سازد که بازهٔ زمانی را نمایان می‌سازد که برابر با مجموع تعداد ساعت‌ها، دقیقه‌ها، ثانیه‌ها و میلی‌ثانیه‌های مشخص‌شده است.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| days | int | تعداد روزها در بخش روزهای بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| hours | int | تعداد ساعت‌ها در بخش ساعت‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| minutes | int | تعداد دقیقه‌ها در بخش دقیقه‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| seconds | int | تعداد ثانیه‌ها در بخش ثانیه‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |
| milliseconds | int | تعداد میلی‌ثانیه‌ها در بخش میلی‌ثانیه‌های بازهٔ زمانی که باید توسط نمونه‌ساز ساخته‌شده نمایش داده شود. |

## TimeSpan::TimeSpan(const TimeSpan\&) سازنده

یک شیء [TimeSpan](../) می‌سازد که بازهٔ زمانی برابر با بازهٔ زمانی نمایان‌شده توسط شیء [TimeSpan](../) مشخص‌شده است.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## موارد مرتبط

* کلاس [TimeSpan](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)