---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و آنها را در آرایه بایتی مشخص شده می‌نویسد.
type: docs
weight: 183
url: /fa/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده شده در آن نوشته می‌شود. |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** که نوشتن از آن شروع می‌شود. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |

### مقدار بازگشتی

تعداد بایت‌های خوانده شده.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | نمای آرایه بایتی که بایت‌های خوانده شده در آن نوشته می‌شود. |
| offset | **int32_t** | موقعیت مبتنی بر صفر در **buffer** که نوشتن از آن شروع می‌شود. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |

### مقدار بازگشتی

تعداد بایت‌های خوانده شده.

## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [FileStream](../)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)