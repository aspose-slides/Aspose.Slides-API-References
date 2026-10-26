---
title: ThreadState
second_title: Aspose.Slides لمرجع API لـ C++
description: حالة الخيط.
type: docs
weight: 326
url: /ar/system.threading/threadstate/
---
## ThreadState enum

State of the thread.

```cpp
enum ThreadState
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) قيد التشغيل. |
| StopRequested | 1 | [Thread](../thread/) تم طلب الإيقاف. |
| SuspendRequested | 2 | [Thread](../thread/) تم طلب التعليق. |
| Background | 4 | يتم تنفيذ الخيط في الخلفية. |
| Unstarted | 8 | [Thread](../thread/) لم يبدأ. |
| Stopped | 16 | [Thread](../thread/) تم إيقافه. |
| WaitSleepJoin | 32 | [Thread](../thread/) ينتظر الانضمام. |
| Suspended | 64 | [Thread](../thread/) تم تعليقه. |
| AbortRequested | 128 | [Thread](../thread/) تم طلب الإنهاء. |
| Aborted | 256 | [Thread](../thread/) تم الإلغاء. |

## انظر أيضًا

* نطاق [System::Threading](../)
* مكتبة [Aspose.Slides](../../)