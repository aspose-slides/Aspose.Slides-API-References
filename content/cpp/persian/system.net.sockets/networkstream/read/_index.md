---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص‌شده می‌نویسد.
type: docs
weight: 196
url: /fa/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد


تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شوند. |
| offset | **int32_t** | جایگاه جابجایی بر حسب بایت در آرایهٔ مشخص‌شده. |
| size | **int32_t** | تعداد بایت‌های قابل خواندن. |

### مقدار بازگشتی

تعداد بایت‌های خوانده‌شده.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد


تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایهٔ بایتی برای نوشتن بایت‌های خوانده‌شده |
| offset | **int32_t** | موقعیت مبتدی از صفر در **buffer** برای شروع نوشتن |
| size | **int32_t** | تعداد بایت‌های خوانده‌شده |

### مقدار بازگشتی

تعداد بایت‌های خوانده‌شده

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [NetworkStream](../)
* فضای نام [System::Net::Sockets](../../)
* کتابخانه [Aspose.Slides](../../../)