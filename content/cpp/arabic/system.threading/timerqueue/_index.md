---
title: TimerQueue
second_title: مرجع API لـ Aspose.Slides للغة C++
description: قائمة تدير كائنات Timer. هذا مجرد تنفيذ. كائنات Timer تسجل هناك بنفسها، لا تحتاج إلى القيام بذلك لاستخدامها - استخدم واجهة برمجة تطبيقات فئة Timer بدلاً من ذلك. هذا نوع singleton مع إدارة الذاكرة تتم بواسطة دالة(دوال) الوصول. يجب ألا تنشئ منه نسخًا مباشرةً.
type: docs
weight: 261
url: /ar/system.threading/timerqueue/
---
## TimerQueue فئة

قائمة تدير كائنات [Timer](../timer/). هذه مجرد تنفيذ. [Timer](../timer/) كائنات تسجل هناك بمفردها، لا تحتاج إلى القيام بذلك لاستخدامها - استخدم [Timer](../timer/) فئة API بدلاً من ذلك. هذا نوع singleton مع إدارة الذاكرة يتم إجراؤها بواسطة دالة(دوال) الوصول. يجب ألا تقوم بإنشاء نسخ منه مباشرةً.

```cpp
class TimerQueue
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | يسجل المؤقت في القائمة. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | يحذف المؤقت من القائمة. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | النسخة الواحدة للتنفيذ. |
| static void [JoinWorkerThread](./joinworkerthread/)() | ينضم إلى خيط العامل. ينتظر إلى الأبد إذا لزم الأمر. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | لا نسخ. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | لا نسخ. |

## انظر أيضًا

* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)