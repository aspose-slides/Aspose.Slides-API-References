---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد مشخصی بایت را از جریان پایه می‌خواند و آنها را در آرایه بایتی مشخص‌شده می‌نویسد.
type: docs
weight: 53
url: /fa/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی بایت را از جریان پایه می‌خواند و آنها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی صفر-مبنا در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شود |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) متد

تعداد مشخصی بایت را از جریان پایه می‌خواند و آنها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود |
| offset | **int32_t** | موقعیتی صفر-مبنا در **buffer** برای شروع نوشتن |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شود |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)