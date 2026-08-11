---
title: ReadAsync()
second_title: Aspose.Slides برای C++ مرجع API
description: به صورت ناهمزمان یک دنباله از بایت‌ها را از جریان فعلی می‌خواند، موقعیت داخل جریان را به اندازه تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.
type: docs
weight: 40
url: /fa/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

به صورت ناهمزمان یک دنباله از بایت‌ها را از جریان فعلی می‌خواند، موقعیت داخل جریان را به اندازه تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود. |
| offset | **int32_t** | موقعیت صفر-پایه در **buffer** که نوشتن از آنجا آغاز می‌شود. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای نظارت بر درخواست‌های لغو استفاده می‌شود. |

### مقدار بازگشت

یک Task که نمایانگر عملیات خواندن ناهمزمان است. مقدار پارامتر TResult شامل کل تعداد بایت‌های خوانده‌شده به بافر است. مقدار نتیجه می‌تواند کمتر از تعداد بایت‌های درخواست‌شده باشد اگر تعداد بایت‌های موجود در حال حاضر کمتر از عدد درخواست‌شده باشد، یا می‌تواند 0 (صفر) باشد اگر به انتهای جریان رسیده باشد.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

به صورت ناهمزمان یک دنباله از بایت‌ها را از جریان فعلی می‌خواند، موقعیت داخل جریان را به اندازه تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شود. |
| offset | **int32_t** | موقعیت صفر-پایه در **buffer** که نوشتن از آنجا آغاز می‌شود. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |

### مقدار بازگشت

یک Task که نمایانگر عملیات خواندن ناهمزمان است. مقدار پارامتر TResult شامل کل تعداد بایت‌های خوانده‌شده به بافر است. مقدار نتیجه می‌تواند کمتر از تعداد بایت‌های درخواست‌شده باشد اگر تعداد بایت‌های موجود در حال حاضر کمتر از عدد درخواست‌شده باشد، یا می‌تواند 0 (صفر) باشد اگر به انتهای جریان رسیده باشد.

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)