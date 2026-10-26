---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌های محدودهٔ مشخص‌شده را از آرایهٔ بایتی مشخص‌شده به جریان می‌نویسد.
type: docs
weight: 92
url: /fa/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

نوشتن بازهٔ مشخصی از بایت‌ها از آرایهٔ بایتی مشخص‌شده به جریان.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های نوشتنی را شامل می‌شود |
| offset | **int32_t** | اندیس مبتنی بر صفر عنصری در **buffer** که بازهٔ نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر بازهٔ نوشتنی |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

نوشتن بازهٔ مشخصی از بایت‌ها از آرایهٔ بایتی مشخص‌شده به جریان.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمأ آرایه‌ای که بایت‌های نوشتنی را شامل می‌شود |
| offset | **int32_t** | اندیس مبتنی بر صفر عنصری در **buffer** که بازهٔ نوشتن از آن شروع می‌شود |
| count | **int32_t** | تعداد عناصر بازهٔ نوشتنی |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [MemoryStream](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)