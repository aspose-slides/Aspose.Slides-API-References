---
title: DateTime()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه ایجاد می‌کند که نمایانگر کوچک‌ترین مقدار ممکن تاریخ و زمان برابر با MinValue است.
type: docs
weight: 1
url: /fa/system/datetime/datetime/
---
## DateTime::DateTime() سازنده

یک نمونه را می‌سازد که نمایانگر کوچک‌ترین مقدار ممکن تاریخ و زمان برابر با MinValue است.

```cpp
constexpr System::DateTime::DateTime()
```

## DateTime::DateTime(int, int, int) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه و روز خاصی است.

```cpp
System::DateTime::DateTime(int year, int month, int day)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |

## DateTime::DateTime(int, int, int, const SharedPtr\<Globalization::Calendar\>\&) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه و روز خاصی در تقویم داده شده است.

```cpp
System::DateTime::DateTime(int year, int month, int day, const SharedPtr<Globalization::Calendar> &calendar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | تقویمی که برای تفسیر **year**, **month** و **day** مشخص‌شده استفاده می‌شود. |

## DateTime::DateTime(int, int, int, int, int, int) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه، روز، ساعت، دقیقه و ثانیه است.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| hour | int | **hour** مربوط به **day** که باید توسط نمونه در حال ساخت نمایانده شود. |
| minute | int | **minute** مربوط به **hour** که باید توسط نمونه در حال ساخت نمایانده شود. |
| second | int | **second** مربوط به **minute** که باید توسط نمونه در حال ساخت نمایانده شود. |

## DateTime::DateTime(int, int, int, int, int, int, DateTimeKind) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه، روز، ساعت، دقیقه و ثانیه است.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, DateTimeKind kind)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| hour | int | **hour** مربوط به **day** که باید توسط نمونه در حال ساخت نمایانده شود. |
| minute | int | **minute** مربوط به **hour** که باید توسط نمونه در حال ساخت نمایانده شود. |
| second | int | **second** مربوط به **minute** که باید توسط نمونه در حال ساخت نمایانده شود. |
| kind | [DateTimeKind](../../datetimekind/) | مقداری که نشان می‌دهد پارامترهای تاریخ و زمان ارائه‌شده یک زمان محلی، زمان UTC یا هیچ‌کدام را مشخص می‌کنند. |

## DateTime::DateTime(int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه، روز، ساعت، دقیقه و ثانیه در تقویم داده شده است.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, const SharedPtr<Globalization::Calendar> &calendar)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| hour | int | **hour** مربوط به **day** که باید توسط نمونه در حال ساخت نمایانده شود. |
| minute | int | **minute** مربوط به **hour** که باید توسط نمونه در حال ساخت نمایانده شود. |
| second | int | **second** مربوط به **minute** که باید توسط نمونه در حال ساخت نمایانده شود. |
| calendar | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | تقویمی که برای تفسیر **year**, **month** و **day** مشخص‌شده استفاده می‌شود. |

## DateTime::DateTime(int, int, int, int, int, int, int, DateTimeKind) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه، روز، ساعت، دقیقه، ثانیه و میلی‌ثانیه است.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, DateTimeKind kind=DateTimeKind::Unspecified)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| hour | int | **hour** مربوط به **day** که باید توسط نمونه در حال ساخت نمایانده شود. |
| minute | int | **minute** مربوط به **hour** که باید توسط نمونه در حال ساخت نمایانده شود. |
| second | int | **second** مربوط به **minute** که باید توسط نمونه در حال ساخت نمایانده شود. |
| millisecond | int | **millisecond** مربوط به **second** که باید توسط نمونه در حال ساخت نمایانده شود. |
| kind | [DateTimeKind](../../datetimekind/) | مقداری که نشان می‌دهد پارامترهای تاریخ و زمان ارائه‌شده یک زمان محلی، زمان UTC یا هیچ‌کدام را مشخص می‌کنند. |

## DateTime::DateTime(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, DateTimeKind) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان سال، ماه، روز، ساعت، دقیقه، ثانیه و میلی‌ثانیه در تقویم داده شده است.

```cpp
System::DateTime::DateTime(int year, int month, int day, int hour, int minute, int second, int millisecond, const SharedPtr<Globalization::Calendar> &calendar, DateTimeKind kind=DateTimeKind::Unspecified)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| year | int | **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| month | int | **month** مربوط به **year** که باید توسط نمونه در حال ساخت نمایانده شود. |
| day | int | **day** مربوط به **month** که باید توسط نمونه در حال ساخت نمایانده شود. |
| hour | int | **hour** مربوط به **day** که باید توسط نمونه در حال ساخت نمایانده شود. |
| minute | int | **minute** مربوط به **hour** که باید توسط نمونه در حال ساخت نمایانده شود. |
| second | int | **second** مربوط به **minute** که باید توسط نمونه در حال ساخت نمایانده شود. |
| millisecond | int | **millisecond** مربوط به **second** که باید توسط نمونه در حال ساخت نمایانده شود. |
| kind | const [SharedPtr](../../sharedptr/)\<[Globalization::Calendar](../../../system.globalization/calendar/)\>\& | مقداری که نشان می‌دهد پارامترهای تاریخ و زمان ارائه‌شده یک زمان محلی، زمان UTC یا هیچ‌کدام را مشخص می‌کنند. |
| calendar | [DateTimeKind](../../datetimekind/) | تقویمی که برای تفسیر **year**, **month** و **day** مشخص‌شده استفاده می‌شود. |

## DateTime::DateTime(int64_t, DateTimeKind) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان تعداد تیک‌ها است.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind=DateTimeKind::Unspecified)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ticks | **int64_t** | تعداد فواصل ۱۰۰ نانوثانیه‌ای که از ۱ ژانویه ۰۰۰۱ ساعت ۰۰:۰۰:۰۰.۰۰۰ در تقویم جرجی عبور کرده است. |
| kind | [DateTimeKind](../../datetimekind/) | مقداری که نشان می‌دهد پارامتر **ticks** یک زمان محلی، زمان UTC یا هیچ‌کدام را مشخص می‌کند. |

## DateTime::DateTime(int64_t, DateTimeKind, bool) سازنده

یک نمونه را می‌سازد که نمایانگر مقدار تاریخ و زمان مشخص‌شده به عنوان تعداد تیک‌ها است. برای استفاده داخلی.

```cpp
System::DateTime::DateTime(int64_t ticks, DateTimeKind kind, bool is_ambiguous_local_dst)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ticks | **int64_t** | تعداد فواصل ۱۰۰ نانوثانیه‌ای که از ۱ ژانویه ۰۰۰۱ ساعت ۰۰:۰۰:۰۰.۰۰۰ در تقویم جرجی عبور کرده است. |
| kind | [DateTimeKind](../../datetimekind/) | مقداری که نشان می‌دهد پارامتر **ticks** یک زمان محلی، زمان UTC یا هیچ‌کدام را مشخص می‌کند. |
| is_ambiguous_local_dst | **bool** | اگر زمان و تاریخ مشخص‌شده مبهم باشد و بتوان آن را به زمان‌های مختلف UTC نگاشت، مقدار true است. |

## DateTime::DateTime(const DateTime\&) سازنده

یک نمونه را به‌صورت کپی می‌سازد.

```cpp
System::DateTime::DateTime(const DateTime &dt)=default
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dt | const [DateTime](../)\& | یک نمونه از کلاس [DateTime](../) برای کپی کردن مقدار تاریخ و زمان نمایانده شده. |

## See Also

* Enum [DateTimeKind](../../datetimekind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [Calendar](../../../system.globalization/calendar/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)