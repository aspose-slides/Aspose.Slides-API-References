---
title: Write()
second_title: Aspose.Slides برای C++ مرجع API
description: بایت‌های زیرمحدودهٔ مشخص‌شده را از آرایهٔ بایتی مشخص به جریان می‌نویسد.
type: docs
weight: 248
url: /fa/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های زیرمحدودهٔ مشخص‌شده را از آرایهٔ بایتی مشخص به جریان می‌نویسد.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود. |
| offset | **int32_t** | نمایهٔ صفر مبنا از **buffer** که زیرمحدودهٔ قابل نوشتن از آنجا آغاز می‌شود. |
| count | **int32_t** | تعداد عناصر در زیرمحدودهٔ قابل نوشتن. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های زیرمحدودهٔ مشخص‌شده را از آرایهٔ بایتی مشخص به جریان می‌نویسد.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | آرایه‌نمایی که بایت‌های قابل نوشتن را شامل می‌شود. |
| offset | **int32_t** | نمایهٔ صفر مبنا از **buffer** که زیرمحدودهٔ قابل نوشتن از آنجا آغاز می‌شود. |
| count | **int32_t** | تعداد عناصر در زیرمحدودهٔ قابل نوشتن. |

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [FileStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)