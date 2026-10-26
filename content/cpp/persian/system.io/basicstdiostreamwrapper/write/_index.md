---
title: Write()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر حالت پیچ‌گذاری باینری باشد، زیرمحدوده مشخصی از بایت‌ها را از آرایه بایت مورد نظر به جریان می‌نویسد؛ در غیر اینصورت زیرمحدوده مشخصی از بایت‌ها را از آرایه بایت مورد نظر به نوع char_type تبدیل کرده و سپس نتیجه را به جریان می‌نویسد.
type: docs
weight: 79
url: /fa/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

اگر حالت پیچ‌گذاری باینری باشد، زیرمحدوده مشخصی از بایت‌ها را از آرایه بایت مورد نظر به جریان می‌نویسد؛ در غیر اینصورت زیرمحدوده مشخصی از بایت‌ها را از آرایه بایت مورد نظر به نوع char_type تبدیل کرده و نتیجه را به جریان می‌نویسد.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه buffer که بایت‌های برای نوشتن را شامل می‌شود |
| offset | **int32_t** | یک ایندکس مبتنی بر صفر از عنصر در **buffer** که زیرمحدوده برای نوشتن از آن آغاز می‌شود |
| count | **int32_t** | تعداد عناصری در زیرمحدوده برای نوشتن |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

زیرمحدوده مشخصی از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه buffer که بایت‌های برای نوشتن را شامل می‌شود |
| offset | **int32_t** | یک ایندکس مبتنی بر صفر از عنصر در **buffer** که زیرمحدوده برای نوشتن از آن آغاز می‌شود |
| count | **int32_t** | تعداد عناصری در زیرمحدوده برای نوشتن |

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BasicSTDIOStreamWrapper](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)