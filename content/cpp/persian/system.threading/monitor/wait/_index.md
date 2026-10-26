---
title: Wait()
second_title: مرجع API Aspose.Slides برای C++
description: قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد. اگر بازهٔ زمان‌سنجی مشخص شده منقضی شود، نخ به صف آماده وارد می‌شود. به‌صورت گزینه‌ای پیش از انتظار از حوزهٔ همگام‌سازی برای زمینهٔ همگام‌سازی خارج می‌شود و پس از آن حوزه را دوباره دریافت می‌کند. پیاده‌سازی نشده.
type: docs
weight: 53
url: /fa/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) متد

قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد. اگر بازهٔ زمان‌سنجی مشخص شده منقضی شود، نخ به صف آماده وارد می‌شود. به‌صورت گزینه‌ای پیش از انتظار از حوزه همگام‌سازی برای زمینهٔ همگام‌سازی خارج می‌شود و پس از آن حوزه را دوباره دریافت می‌کند. پیاده سازی نشده.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) متد

قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد. اگر بازهٔ زمان‌سنجی مشخص شده منقضی شود، نخ به صف آماده وارد می‌شود. به‌صورت گزینه‌ای پیش از انتظار از حوزه همگام‌سازی برای زمینهٔ همگام‌سازی خارج می‌شود و پس از آن حوزه را دوباره دریافت می‌کند. پیاده سازی نشده.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) متد

قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد. اگر بازهٔ زمان‌سنجی مشخص شده منقضی شود، نخ به صف آماده وارد می‌شود. پیاده سازی نشده.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) متد

قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد. اگر بازهٔ زمان‌سنجی مشخص شده منقضی شود، نخ به صف آماده وارد می‌شود. پیاده سازی نشده.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) متد

قفل را از یک شی آزاد می‌کند و نخ فعلی را تا دریافت مجدد قفل مسدود می‌سازد پیاده سازی نشده.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [Monitor](../)
* کلاس [TimeSpan](../../../system/timespan/)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)