---
title: CancellationTokenRegistration
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک ثبت برای بازگردانی توکن لغو است.
type: docs
weight: 27
url: /fa/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration کلاس

نمایانگر ثبت یک بازگردانی توکن لغو است.

```cpp
class CancellationTokenRegistration
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Dispose](./dispose/)() | ثبت را از بین می‌برد و بازگردانی را از [CancellationTokenSource](../cancellationtokensource/) مرتبط حذف می‌کند. پس از فراخوانی این متد، بازگردانی ثبت‌شده دیگر زمانی که [CancellationTokenSource](../cancellationtokensource/) مرتبط لغو شود فراخوانی نخواهد شد. |
## توضیحات

این کلاس امکان حذف ثبت یک بازگردانی از یک توکن لغو را فراهم می‌کند. هنگام حذف، بازگردانی را از [CancellationTokenSource](../cancellationtokensource/) مرتبط حذف می‌کند. این کلاس نباید به‌صورت مستقیم ساخته شود - این کلاس توسط متدهای ثبت [CancellationToken](../cancellationtoken/) برگردانده می‌شود.

## موارد مرتبط

* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)