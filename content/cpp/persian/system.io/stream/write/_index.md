---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌های محدوده‌ی مشخص‌شده را از آرایه بایت تعیین‌شده به جریان می‌نویسد.
type: docs
weight: 53
url: /fa/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های محدوده‌ی مشخص‌شده را از آرایه بایت تعیین‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های مورد نوشتن را شامل می‌شود |
| offset | **int32_t** | اندازی صفر-مبنای عنصر در **buffer** که محدوده‌ی نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در محدوده‌ی نوشتن |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های محدوده‌ی مشخص‌شده را از آرایه بایت تعیین‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه‌ای که بایت‌های مورد نوشتن را در خود دارد |
| offset | **int32_t** | اندازی صفر-مبنای عنصر در **buffer** که محدوده‌ی نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در محدوده‌ی نوشتن |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) متد

بایت‌های محدوده‌ی مشخص‌شده را از آرایه بایت تعیین‌شده به جریان می‌نویسد.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | اندازه‌ی آرایه پشته |

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | آرایه پشته‌ای که بایت‌های مورد نوشتن را در بر دارد |
| offset | **int32_t** | اندازی صفر-مبنای عنصر در **buffer** که محدوده‌ی نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در محدوده‌ی نوشتن |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) متد

بایت‌های محدوده‌ی مشخص‌شده را از اسپن بایت تعیین‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | اسپن بایتی که بایت‌های نوشته‌شده از آن خوانده می‌شود |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Stream](../)
* کلاس [ReadOnlySpan](../../../system/readonlyspan/)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)