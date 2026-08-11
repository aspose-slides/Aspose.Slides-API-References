---
title: Read()
second_title: Aspose.Slides برای مرجع API C++
description: اگر حالت بسته‌بندی باینری باشد، تعداد مشخصی بایت را از جریان می‌خواند، در غیر این صورت تعداد مشخصی کاراکتر را می‌خواند و به نوع uint8_t تبدیل می‌کند. نتیجهٔ خواندن را در آرایه بایتی مشخص‌شده می‌نویسد. پشتیبانی نمی‌شود!
type: docs
weight: 66
url: /fa/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

اگر حالت بسته‌بندی باینری باشد، تعداد مشخصی بایت را از جریان می‌خواند، در غیر این صورت تعداد مشخصی کاراکتر را می‌خواند و به نوع **uint8_t** تبدیل می‌کند. نتیجه خواندن را در آرایه بایتی مشخص‌شده می‌نویسد. پشتیبانی نمی‌شود!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی با ایندکس صفر در **buffer** که نوشتن از آن آغاز می‌شود |
| count | **int32_t** | تعداد بایت‌های خوانده‌شده |

### مقدار بازگشت

تعداد بایت‌ها یا کاراکترهای خوانده‌شده

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی بایت را از جریان می‌خواند و آنها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی با ایندکس صفر در **buffer** که نوشتن از آن آغاز می‌شود |
| count | **int32_t** | تعداد بایت‌های خوانده‌شده |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BasicSTDOStreamWrapper](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)