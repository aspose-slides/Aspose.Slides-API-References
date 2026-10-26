---
title: WriteAsync()
second_title: مرجع API Aspose.Slides برای C++
description: به‌صورت ناهمزمان یک دنباله بایت را به جریان جاری می‌نویسد، موقعیت فعلی در این جریان را به مقدار بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند.
type: docs
weight: 261
url: /fa/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) متد

به‌صورت ناهمزمان یک دنباله بایت را به جریان جاری می‌نویسد، موقعیت فعلی در این جریان را به مقدار بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای که شامل بایت‌های مورد نوشتن است. |
| offset | **int32_t** | یک ایندکس صفر-پایه از عنصر در **buffer** که زیرمحدوده‌ای که باید نوشته شود از آن شروع می‌شود. |
| count | **int32_t** | تعداد عناصر در زیرمحدوده‌ای که باید نوشته شود. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای نظارت بر درخواست‌های لغو مورد استفاده قرار می‌گیرد. |

### مقدار بازگشت

یک تسک که نمایانگر عملیات نوشتن ناهمزمان است.

## موارد مرتبط

* تعریف نوع [TaskPtr](../../../system/taskptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [CancellationToken](../../../system.threading/cancellationtoken/)
* کلاس [FileStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)