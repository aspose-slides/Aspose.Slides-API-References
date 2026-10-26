---
title: Join()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينضم إلى الخيط المُدار. يقوم بالانتظار غير المحدود إذا لزم الأمر.
type: docs
weight: 196
url: /ar/system.threading/thread/join/
---
## Thread::Join() طريقة

ينضم إلى الخيط المُدار. يقوم بالانتظار غير المحدود إذا لزم الأمر.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) طريقة

ينضم إلى الخيط المُدار. يقوم بالانتظار المحدود.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| millisecondsTimeout | int | مهلة الانتظار بالمللي ثانية. |

### قيمة الإرجاع

True إذا تم الانضمام إلى الخيط بنجاح، false إذا تجاوزت المهلة.

## Thread::Join(TimeSpan) طريقة

ينضم إلى الخيط المُدار. يقوم بالانتظار المحدود.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [TimeSpan](../../../system/timespan/) محدد إلى مقدار الوقت للانتظار حتى ينتهي الخيط. |

### قيمة الإرجاع

True إذا تم الانضمام إلى الخيط بنجاح، false إذا تجاوزت المهلة.

## انظر أيضًا

* فئة [Thread](../)
* فئة [TimeSpan](../../../system/timespan/)
* مساحة الاسم [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)