---
title: FlushAsync()
second_title: مرجع API Aspose.Slides برای C++
description: به صورت غیرهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند.
type: docs
weight: 118
url: /fa/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) متد

به صورت غیرهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای مانیتور کردن درخواست‌های لغو استفاده می‌شود. |

### مقدار بازگشت

یک کار که نمایانگر عملیات غیرهمزمان خالی‌سازی است.

## Stream::FlushAsync() متد

به صورت غیرهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### مقدار بازگشت

یک کار که نمایانگر عملیات غیرهمزمان خالی‌سازی است.

## مراجع

* Typedef [TaskPtr](../../../system/taskptr/)
* کلاس [CancellationToken](../../../system.threading/cancellationtoken/)
* کلاس [Stream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)