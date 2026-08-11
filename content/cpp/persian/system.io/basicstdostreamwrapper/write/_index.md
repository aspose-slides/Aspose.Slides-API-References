---
title: Write()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر حالت بسته‌بندی باینری باشد، زیرمجموعهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد، در غیر اینصورت زیرمجموعهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص‌شده به نوع char_type تبدیل می‌کند و سپس نتیجه را به جریان می‌نویسد.
type: docs
weight: 79
url: /fa/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

اگر حالت بسته‌بندی باینری باشد، زیرمجموعهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد، در غیر این صورت زیرمجموعهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص‌شده به نوع char_type تبدیل می‌کند و سپس نتیجه را به جریان می‌نویسد.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های برای نوشتن را دربر می‌گیرد |
| offset | **int32_t** | اندیس مبتنی بر صفر از عنصر در **buffer** که زیرمجموعه برای نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در زیرمجموعه برای نوشتن |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

زیرمجموعهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه‌ای که بایت‌های برای نوشتن را دربر می‌گیرد |
| offset | **int32_t** | اندیس مبتنی بر صفر از عنصر در **buffer** که زیرمجموعه برای نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در زیرمجموعه برای نوشتن |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [BasicSTDOStreamWrapper](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)