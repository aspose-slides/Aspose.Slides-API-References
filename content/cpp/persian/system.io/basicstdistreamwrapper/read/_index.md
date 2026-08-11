---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر حالت بسته‌بندی باینری باشد، تعداد بایت مشخص‌شده را از جریان می‌خواند، در غیر این صورت تعداد کاراکترهای مشخص‌شده را می‌خواند و به نوع uint8_t تبدیل می‌کند. نتیجهٔ خواندن را در آرایه بایتی مشخص‌شده می‌نویسد.
type: docs
weight: 66
url: /fa/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

اگر حالت بسته‌بندی باینری باشد، تعداد بایت مشخص‌شده را از جریان می‌خواند، در غیر این صورت تعداد کاراکترهای مشخص‌شده را می‌خواند و به نوع **uint8_t** تبدیل می‌کند. نتیجهٔ خواندن را در آرایه بایتی مشخص-شده می‌نویسد.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌ها یا کاراکترهای خوانده‌شده

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## مراجع

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BasicSTDIStreamWrapper](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)