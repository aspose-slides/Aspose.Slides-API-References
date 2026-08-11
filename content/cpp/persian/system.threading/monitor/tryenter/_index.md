---
title: TryEnter()
second_title: Aspose.Slides برای C++ مرجع API
description: تلاش برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص. پیاده‌سازی نشده.
type: docs
weight: 27
url: /fa/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) متد

تلاش برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص. پیاده‌سازی نشده.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) متد

تلاش برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص و به‌صورت اتمی مقدار را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) متد

تلاش، برای تعداد میلی‌ثانیه‌های مشخص‌شده، برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص. پیاده‌سازی نشده.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) متد

تلاش، برای مدت زمان مشخص‌شده، برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص. پیاده‌سازی نشده.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) متد

تلاش، برای مدت زمان مشخص‌شده، برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص و به‌صورت اتمی مقدار را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) متد

تلاش، برای مدت زمان مشخص‌شده، برای به‌دست‌آوردن یک قفل اختصاصی روی شیء مشخص و به‌صورت اتمی مقدار را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Monitor](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای‌نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)