---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: تعدادی مشخص از بایت‌ها را از جریان می‌خواند و آن‌ها را در آرایه بایتی مشخص‌شده می‌نویسد.
type: docs
weight: 391
url: /fa/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی از بایت‌ها را از جریان می‌خواند و آن‌ها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده به آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی با ایندکس صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های خوانده‌شده |

### مقدار برگشتی

تعداد بایت‌های خوانده‌شده

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی از بایت‌ها را از جریان می‌خواند و آن‌ها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده به آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی با ایندکس صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌های خوانده‌شده |

### مقدار برگشتی

تعداد بایت‌های خوانده‌شده

## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [SslStream](../)
* فضای‌نام [System::Net::Security](../../)
* کتابخانه [Aspose.Slides](../../../)