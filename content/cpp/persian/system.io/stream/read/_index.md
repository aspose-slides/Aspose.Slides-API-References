---
title: Read()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایه بایت مشخص‌شده می‌نویسد.
type: docs
weight: 27
url: /fa/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایه بایت مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی مبتنی بر صفر در **buffer** که نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایه بایت مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی مبتنی بر صفر در **buffer** که نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) متد

تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایه بایت مشخص‌شده می‌نویسد.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | اندازهٔ آرایهٔ پشته |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | آرایه پشتهٔ بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی مبتنی بر صفر در **buffer** که نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## Stream::Read(const System::Span\<uint8_t\>\&) متد

تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در بازه بایت مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | بازه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Stream](../)
* کلاس [Span](../../../system/span/)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)