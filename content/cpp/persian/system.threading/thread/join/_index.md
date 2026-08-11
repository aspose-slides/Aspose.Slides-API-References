---
title: Join()
second_title: مرجع API Aspose.Slides برای C++
description: رشته مدیریت‌شده را می‌پیوندد. در صورت نیاز، انتظار نامحدودی انجام می‌دهد.
type: docs
weight: 196
url: /fa/system.threading/thread/join/
---
## Thread::Join() متد


رشته مدیریت‌شده را می‌پیوندد. در صورت لزوم، انتظار نامحدودی انجام می‌دهد.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) متد


رشته مدیریت‌شده را می‌پیوندد. انتظار محدودی انجام می‌دهد.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| millisecondsTimeout | int | زمان انتظار برحسب میلی‌ثانیه. |

### مقدار برگشتی

True اگر رشته با موفقیت پیوست شد، false اگر مهلت زمان پایان یافت.

## Thread::Join(TimeSpan) متد


رشته مدیریت‌شده را می‌پیوندد. انتظار محدودی انجام می‌دهد.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | یک [TimeSpan](../../../system/timespan/) تنظیم‌شده به مقدار زمان انتظار برای خاتمه یافتن رشته. |

### مقدار برگشتی

True اگر رشته با موفقیت پیوست شد، false اگر مهلت زمان پایان یافت.

## موارد مرتبط

* کلاس [Thread](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)