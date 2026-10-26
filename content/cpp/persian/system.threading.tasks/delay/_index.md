---
title: Delay()
second_title: Aspose.Slides برای C++ مرجع API
description: یک تسک ایجاد می‌کند که پس از یک تأخیر زمانی تکمیل می‌شود.
type: docs
weight: 105
url: /fa/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) تابع

یک تسک ایجاد می‌کند که پس از یک تأخیر زمانی تکمیل می‌شود.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | تعداد میلی‌ثانیه‌هایی که باید قبل از تکمیل تسک بازگردانده‌شده صبر شود، یا -1 برای انتظار نامحدود. |

### مقدار بازگشت

یک تسک که نمایانگر تأخیر زمانی است.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) تابع

یک تسک ایجاد می‌کند که پس از یک تأخیر زمانی تکمیل می‌شود و می‌تواند لغو شود.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | تعداد میلی‌ثانیه‌هایی که باید قبل از تکمیل تسک بازگردانده‌شده صبر شود، یا -1 برای انتظار نامحدود. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | توکن لغو که می‌توان از آن برای لغو تأخیر استفاده کرد. |

### مقدار بازگشت

یک تسک که نمایانگر تأخیر زمانی است.

## موارد مرتبط

* Typedef [TaskPtr](../../system/taskptr/)
* کلاس [CancellationToken](../../system.threading/cancellationtoken/)
* فضای نام [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)