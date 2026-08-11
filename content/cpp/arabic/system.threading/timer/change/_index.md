---
title: Change()
second_title: Aspose.Slides للمرجع API لـ C++
description: يعيد جدولة المؤقت أو يلغيه.
type: docs
weight: 14
url: /ar/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) طريقة

يعيد جدولة المؤقت أو يلغيه.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) قبل الاستدعاء التالي لدالة رد النداء، بالمللي ثانية؛ القيم السلبية تلغي المؤقت حتى لو كان مُجدولًا. |
| period | **int64_t** | [Timeout](../../timeout/) بين الاستدعاءات المتتابعة لدالة رد النداء، بالمللي ثانية؛ القيم غير الموجبة تعني أن المؤقت يجب أن يُنفّذ مرة واحدة فقط. |

## Timer::Change(System::TimeSpan, System::TimeSpan) طريقة

يعيد جدولة المؤقت أو يلغيه.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) قبل الاستدعاء التالي لدالة رد النداء؛ القيم السلبية تلغي المؤقت حتى لو كان مُجدولًا. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) بين الاستدعاءات المتتابعة لدالة رد النداء؛ القيم غير الموجبة تعني أن المؤقت يجب أن يُنفّذ مرة واحدة فقط. |

## انظر أيضًا

* الفئة [Timer](../)
* الفئة [TimeSpan](../../../system/timespan/)
* النطاق [System::Threading](../../)
* المكتبة [Aspose.Slides](../../../)