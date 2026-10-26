---
title: Read()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایه بایت مشخص‌شده می‌نویسد.
type: docs
weight: 79
url: /fa/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

خواندن تعداد بایت مشخص‌شده از جریان و نوشتن آن‌ها در آرایه بایت مشخص‌شده.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایت برای نوشتن بایت‌های خوانده شده |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های مورد خواندن |

### مقدار بازگشت

تعداد بایت‌های خوانده شده

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

خواندن تعداد بایت مشخص‌شده از جریان و نوشتن آن‌ها در آرایه بایت مشخص‌شده.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایت برای نوشتن بایت‌های خوانده شده |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های مورد خواندن |

### مقدار بازگشت

تعداد بایت‌های خوانده شده

## مراجعه

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [MemoryStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)