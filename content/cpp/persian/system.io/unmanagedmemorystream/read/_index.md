---
title: Read()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد مشخصی بایت را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد.
type: docs
weight: 144
url: /fa/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی بایت را از جریان می‌خواند و در آرایه بایت مشخص شده می‌نویسد.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایت برای نوشتن بایت‌های خوانده شده |
| offset | **int32_t** | موقعیتی مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های خوانده شده |

### مقدار بازگشتی

تعداد بایت‌های خوانده شده

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی بایت را از جریان می‌خواند و در آرایه بایت مشخص شده می‌نویسد.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایت برای نوشتن بایت‌های خوانده شده |
| offset | **int32_t** | موقعیتی مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های خوانده شده |

### مقدار بازگشتی

تعداد بایت‌های خوانده شده

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [UnmanagedMemoryStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)