---
title: WaitOne()
second_title: مرجع API Aspose.Slides لـ C++
description: يقفل mutex. ينفذ انتظارًا غير محدود إذا لزم الأمر.
type: docs
weight: 53
url: /ar/system.threading/mutex/waitone/
---
## Mutex::WaitOne() طريقة

يقفل mutex. ينفذ انتظارًا غير محدود إذا كان ذلك ضروريًا.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### قيمة الإرجاع

دائمًا ما تُرجِع true لأنّه لا يعود حتى يتم قفل mutex.

## Mutex::WaitOne(int) طريقة

يقفل mutex. ينفذ انتظارًا إذا كان ذلك ضروريًا.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| millisecondsTimeout | int | مهلة الانتظار بالميلي ثانية. |

### قيمة الإرجاع

تُرجِع true إذا تم قفل mutex أو false إذا تجاوزت المهلة.

## Mutex::WaitOne(TimeSpan) طريقة

يقفل mutex. ينفذ انتظارًا إذا كان ذلك ضروريًا.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) يمثل عدد الميلي ثانية للانتظار، أو [System::TimeSpan](../../../system/timespan/) يمثل -1 ميلي ثانية للانتظار إلى أجل غير مسمى. |

### قيمة الإرجاع

تُرجِع true إذا تم قفل mutex أو false إذا تجاوزت المهلة.

## انظر أيضًا

* فئة [Mutex](../)
* فئة [TimeSpan](../../../system/timespan/)
* فضاء الاسم [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)