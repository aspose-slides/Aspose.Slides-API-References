---
title: Write()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر حالت بسته‌بندی binary باشد، بازهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص به جریان می‌نویسد؛ در غیر این صورت بازهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص به نوع char_type تبدیل می‌کند و سپس نتیجه را به جریان می‌نویسد. پشتیبانی نمی‌شود!
type: docs
weight: 79
url: /fa/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

اگر حالت بسته‌بندی binary باشد، بازهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص به جریان می‌نویسد، در غیر این صورت بازهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص به نوع char_type تبدیل می‌کند و سپس نتیجه را به جریان می‌نویسد. پشتیبانی نمی‌شود!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های مورد نیاز برای نوشتن را شامل می‌شود. |
| offset | **int32_t** | نمایه‌ای مبتنی بر صفر از عنصر در **buffer** که بازهٔ نوشتن از آن شروع می‌شود. |
| count | **int32_t** | تعداد عناصر در بازهٔ نوشتن. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

بازهٔ مشخصی از بایت‌ها را از آرایهٔ بایت مشخص به جریان می‌نویسد.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نما (view) آرایه‌ای که بایت‌های مورد نیاز برای نوشتن را شامل می‌شود |
| offset | **int32_t** | نمایه‌ای مبتنی بر صفر از عنصر در **buffer** که بازهٔ نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر در بازهٔ نوشتن |

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BasicSTDIStreamWrapper](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)