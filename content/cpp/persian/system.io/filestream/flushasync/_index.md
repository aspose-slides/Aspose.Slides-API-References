---
title: FlushAsync()
second_title: Aspose.Slides برای C++ مرجع API
description: به‌صورت ناهم‌زمان تمام بافرهای این جریان را پاک می‌کند، داده‌های بافرشده را به دستگاه زیرین می‌نویسد و درخواست‌های لغو را نظارت می‌نماید.
type: docs
weight: 157
url: /fa/system.io/filestream/flushasync/
---
## متد FileStream::FlushAsync(const Threading::CancellationToken\&) 


به‌صورت ناهم‌زمان تمام بافرهای این جریان را پاک می‌کند، داده‌های بافرشده را به دستگاه پایه می‌نویسد و درخواست‌های لغو را مانیتور می‌کند.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | توکنی که برای مانیتور کردن درخواست‌های لغو استفاده می‌شود. |

### مقدار بازگشت

یک Task که نمایانگر عملیات Flush ناهم‌زمان است.

## موارد مرتبط

* Typedef [TaskPtr](../../../system/taskptr/)
* کلاس [CancellationToken](../../../system.threading/cancellationtoken/)
* کلاس [FileStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)