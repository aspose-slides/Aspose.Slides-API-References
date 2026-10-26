---
title: Cancel()
second_title: مرجع API Aspose.Slides برای C++
description: درخواست لغو را اعلام می‌کند.
type: docs
weight: 40
url: /fa/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() متد

درخواست لغو را اعلام می‌کند.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## توضیحات

تمام callbackهای ثبت‌شده فراخوانی می‌شوند.

فراخوانی‌های بعدی به [get_IsCancellationRequested()](../get_iscancellationrequested/) مقدار true باز می‌گردانند.

Callbackها به‌صورت همزمان در طول این فراخوانی اجرا می‌شوند.

## موارد مرتبط

* کلاس [CancellationTokenSource](../)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)