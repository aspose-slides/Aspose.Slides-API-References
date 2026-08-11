---
title: Write()
second_title: Aspose.Slides برای C++ مرجع API
description: بایت‌های زیرمجموعهٔ مشخص‌شده را از آرایهٔ بایت مشخص به جریان زیرین می‌نویسد.
type: docs
weight: 66
url: /fa/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های زیرمجموعهٔ مشخص‌شده را از آرایهٔ بایت مشخص به جریان زیرین می‌نویسد.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود |
| offset | **int32_t** | شاخصی پایهٔ صفر برای عنصر موجود در **buffer** که زیرمجموعهٔ قابل نوشتن از آنجا شروع می‌شود |
| count | **int32_t** | تعداد عناصر در زیرمجموعهٔ قابل نوشتن |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

بایت‌های زیرمجموعهٔ مشخص‌شده را از آرایهٔ بایت مشخص به جریان زیرین می‌نویسد.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود |
| offset | **int32_t** | شاخصی پایهٔ صفر برای عنصر موجود در **buffer** که زیرمجموعهٔ قابل نوشتن از آنجا شروع می‌شود |
| count | **int32_t** | تعداد عناصر در زیرمجموعهٔ قابل نوشتن |

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [BufferedStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)