---
title: ThreadPoolImpl
second_title: مرجع API ل Aspose.Slides للغة C++
description: بيانات داخلية لتجمع الخيوط. هذا نوع أحادي مع إدارة الذاكرة يتم تنفيذها بواسطة دالة (دوال) الوصول. يجب ألا تقوم بإنشاء مثيلات له مباشرةً.
type: docs
weight: 235
url: /ar/system.threading/threadpoolimpl/
---
## ThreadPoolImpl فئة


[Thread](../thread/) بيانات داخلية للمجمع. هذا نوع أحادي مع إدارة الذاكرة يتم تنفيذها بواسطة دالة (دوال) الوصول. يجب ألا تقوم بإنشاء مثيلات له مباشرةً.

```cpp
class ThreadPoolImpl
```

## الطرق

| Method | Description |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | يُحصل على عدد الخيوط المتاحة. |
| static **bool**\& [GetInitialized](./getinitialized/)() | يُحصل على حالة التهيئة الأحادية. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | يُحصل على الحد الأقصى لعدد الخيوط المتزامنة. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | يُحصل على الحد الأدنى لعدد الخيوط التي يتم إنشاؤها بواسطة المجمع. |
| void [JoinAll](./joinall/)() | ينضم إلى جميع الخيوط المملوكة. ينتظر إلى ما لا نهاية. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | يضيف عنصر عمل إلى قائمة الانتظار. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | يضبط عدد الخيوط المملوكة للمجمع. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | يضبط الحد الأدنى لعدد الخيوط المملوكة للمجمع. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | منشئ. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | مدمر. ينضم إلى جميع الخيوط إذا لم يتم إنهاؤها بعد. |

## انظر أيضًا

* النطاق [System::Threading](../)
* المكتبة [Aspose.Slides](../../)