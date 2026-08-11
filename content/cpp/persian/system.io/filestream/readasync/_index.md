---
title: ReadAsync()
second_title: مرجع API Aspose.Slides برای C++
description: به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت جریان را به تعداد بایت‌های خوانده‌شده پیش می‌راند و درخواست‌های لغو را پایش می‌کند.
type: docs
weight: 196
url: /fa/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) متد


به‌صورت ناهمزمان یک دنباله بایت را از جریان جاری می‌خواند، موقعیت جریان را به تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایهٔ بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شوند. |
| offset | **int32_t** | یک موقعیت صفر-پایه در **buffer** برای شروع نوشتن. |
| count | **int32_t** | تعداد بایت‌های قابل خواندن. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای پایش درخواست‌های لغو استفاده می‌شود. |

### مقدار بازگشت

یک تسکی که نمایانگر عملیات خواندن ناهمزمان است. مقدار پارامتر TResult شامل کل تعداد بایت‌های خوانده‌شده در buffer است. مقدار نتیجه می‌تواند کمتر از تعداد بایت‌های درخواست‌شده باشد اگر تعداد بایت‌های موجود در حال حاضر کمتر از مقدار درخواست‌شده باشد، یا می‌تواند صفر (0) باشد اگر به انتهای جریان رسیده باشد.

## موارد مرتبط

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)