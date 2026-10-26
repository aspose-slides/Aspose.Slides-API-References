---
title: WaitOne()
second_title: Aspose.Slides برای C++ مرجع API
description: سیمفور را قفل می‌کند. در صورت لزوم، انتظار نامحدود انجام می‌دهد.
type: docs
weight: 40
url: /fa/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() method

سیمفور را قفل می‌کند. در صورت لزوم، انتظار نامحدود انجام می‌دهد.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### مقدار بازگشت

همیشه true برمی‌گرداند زیرا تا زمانی که سیمفور قفل نشود، برنمی‌گردد.

## Semaphore::WaitOne(int) method

سیمفور را قفل می‌کند. در صورت لزوم، انتظار انجام می‌دهد.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsTimeout | int | زمان‌انتظار بر حسب میلی‌ثانیه. |

### مقدار بازگشت

اگر سیمفور قفل شده باشد true برمی‌گرداند یا اگر زمان‌سرویس بیش از حد باشد false برمی‌گرداند.

## موارد مرتبط

* Class [Semaphore](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)