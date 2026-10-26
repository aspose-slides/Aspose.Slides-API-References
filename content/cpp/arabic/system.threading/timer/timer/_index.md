---
title: Timer()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: منشئ.
type: docs
weight: 1
url: /ar/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) مُنشئ

منشئ.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | الدالة التي يتم استدعاؤها من قبل المؤقت. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) مُنشئ

منشئ.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | الدالة التي يتم استدعاؤها من قبل المؤقت. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | معلمة دالة النداء. |
| dueTime | **int64_t** | [Timeout](../../timeout/) قبل أول استدعاء للدالة النداء، بالمللي ثانية؛ القيم السلبية لا تُجدول المؤقت بعد الإنشاء بحيث يمكن إعادة جدولتة لاحقاً. |
| period | **int64_t** | [Timeout](../../timeout/) بين الاستدعاءات المتتابعة للدالة النداء، بالمللي ثانية؛ القيم غير الموجبة تعني أن المؤقت يجب أن يُنفّذ مرة واحدة فقط. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) مُنشئ

منشئ.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | الدالة التي يتم استدعاؤها من قبل المؤقت. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | معلمة دالة النداء. |
| dueTime | [System::TimeSpan](../../../system/timespan/) [Timeout](../../timeout/) قبل أول استدعاء للدالة النداء؛ القيم السلبية لا تُجدول المؤقت بعد الإنشاء بحيث يمكن إعادة جدولتة لاحقاً. |
| period | [System::TimeSpan](../../../system/timespan/) [Timeout](../../timeout/) بين الاستدعاءات المتتابعة للدالة النداء؛ القيم غير الموجبة تعني أن المؤقت يجب أن يُنفّذ مرة واحدة فقط. |

## انظر أيضًا

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Timer](../)
* فئة [Object](../../../system/object/)
* فئة [TimeSpan](../../../system/timespan/)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)