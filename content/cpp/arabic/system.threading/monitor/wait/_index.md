---
title: Wait()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل. إذا انقضت فترة المهلة المحددة، يدخل الخيط إلى طابور الجاهزية. يمكن اختيارياً الخروج من نطاق المزامنة للسياق المتزامن قبل الانتظار وإعادة اكتساب النطاق بعد ذلك. غير مُطبق.
type: docs
weight: 53
url: /ar/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) طريقة

يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل. إذا انقضت فترة المهلة المحددة، يدخل الخيط إلى طابور الجاهزية. يمكن اختيارياً الخروج من نطاق المزامنة للسياق المتزامن قبل الانتظار وإعادة اكتساب النطاق بعد ذلك. غير مُطبق.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) طريقة

يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل. إذا انقضت فترة المهلة المحددة، يدخل الخيط إلى طابور الجاهزية. يمكن اختيارياً الخروج من نطاق المزامنة للسياق المتزامن قبل الانتظار وإعادة اكتساب النطاق بعد ذلك. غير مُطبق.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) طريقة

يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل. إذا انقضت فترة المهلة المحددة، يدخل الخيط إلى طابور الجاهزية. غير مُطبق.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) طريقة

يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل. إذا انقضت فترة المهلة المحددة، يدخل الخيط إلى طابور الجاهزية. غير مُطبق.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) طريقة

يطلق القفل عن كائن ويحجب الخيط الحالي حتى يستعيد القفل غير مُطبق.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Monitor](../)
* فئة [TimeSpan](../../../system/timespan/)
* مساحة أسماء [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)