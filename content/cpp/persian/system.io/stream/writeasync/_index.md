---
title: WriteAsync()
second_title: Aspose.Slides برای C++ مرجع API
description: به صورت ناهمزمان یک دنباله بایت را در جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازه بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.
type: docs
weight: 66
url: /fa/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) متد

به‌صورت ناهمزمان یک دنباله بایت را در جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازه بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود. |
| offset | **int32_t** | یک ایندکس صفر مبنا از عنصر در **buffer** که زیرمحدوده‌ی نوشتن از آنجا شروع می‌شود. |
| count | **int32_t** | تعداد عناصر در زیرمحدوده‌ی قابل نوشتن. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای نظارت بر درخواست‌های لغو استفاده می‌شود. |

### مقدار بازگشت

یک تسکی که نمایانگر عملیات نوشتن ناهمزمان است.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

به‌صورت ناهمزمان یک دنباله بایت را در جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازه بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که بایت‌های قابل نوشتن را شامل می‌شود. |
| offset | **int32_t** | یک ایندکس صفر مبنا از عنصر در **buffer** که زیرمحدوده‌ی نوشتن از آنجا شروع می‌شود. |
| count | **int32_t** | تعداد عناصر در زیرمحدوده‌ی قابل نوشتن. |

### مقدار بازگشت

یک تسکی که نمایانگر عملیات نوشتن ناهمزمان است.

## موارد مرتبط

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)