---
title: TimerQueue
second_title: مرجع API Aspose.Slides برای C++
description: صفّه‌ای که اشیای Timer را مدیریت می‌کند. این فقط یک پیاده‌سازی است. اشیای Timer خود به خود در آن ثبت می‌شوند، برای استفاده از آن‌ها نیازی به این کار ندارید - به‌جای آن از API کلاس Timer استفاده کنید. این یک نوع تک‌نمونه است که مدیریت حافظه توسط توابع دسترسی انجام می‌شود. شما هرگز نباید مستقیماً نمونه‌های آن را ایجاد کنید.
type: docs
weight: 261
url: /fa/system.threading/timerqueue/
---
## کلاس TimerQueue

صفّه‌ای که اشیای [Timer](../timer/) را مدیریت می‌کند. این فقط یک پیاده‌سازی است. اشیای [Timer](../timer/) خود به خود در آن ثبت می‌شوند، برای استفاده از آن‌ها نیازی به این کار ندارید - به‌جای آن از API کلاس [Timer](../timer/) استفاده کنید. این یک نوع تک‌نمونه با مدیریت حافظه توسط توابع دسترسی است. شما نباید مستقیماً نمونه‌های آن را ایجاد کنید.

```cpp
class TimerQueue
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | زمان‌ساز را در صف ثبت می‌کند. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | زمان‌ساز را از صف حذف می‌کند. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | تک‌نمونه پیاده‌سازی. |
| static void [JoinWorkerThread](./joinworkerthread/)() | به رشتهٔ کارگر می‌پیوندد. در صورت نیاز به‌صورت نامحدود انتظار می‌کشد. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | بدون کپی‌برداری. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | بدون کپی‌برداری. |

## موارد مرتبط

* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)