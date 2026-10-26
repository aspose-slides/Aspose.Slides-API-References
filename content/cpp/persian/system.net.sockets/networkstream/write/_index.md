---
title: Write()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌های زیرمحدودهٔ مشخص‌شده را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد.
type: docs
weight: 209
url: /fa/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد


زیرمحدودهٔ مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که حاوی بایت‌های قابل‌نوشتن است. |
| offset | **int32_t** | جابه‌جایی (آفست) بر حسب بایت در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد عناصر در زیرمحدودهٔ قابل نوشتن. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد


زیرمحدودهٔ مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایت مشخص‌شده به جریان می‌نویسد.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه‌ای که حاوی بایت‌های قابل نوشتن است |
| offset | **int32_t** | یک شاخص صفر-پایه از عنصر در **buffer** که زیرمحدودهٔ قابل نوشتن از آنجا شروع می‌شود |
| size | **int32_t** | تعداد عناصر در زیرمحدودهٔ قابل نوشتن |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [NetworkStream](../)
* فضای نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)