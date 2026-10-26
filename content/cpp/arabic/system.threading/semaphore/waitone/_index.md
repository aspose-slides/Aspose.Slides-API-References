---
title: WaitOne()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقفل semaphore. ينفذ انتظارًا غير محدود إذا كان ذلك ضروريًا.
type: docs
weight: 40
url: /ar/system.threading/semaphore/waitone/
---
## طريقة Semaphore::WaitOne() method


يقفل semaphore. ينفذ انتظارًا غير محدود إذا كان ذلك ضروريًا.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### قيمة الإرجاع

دائمًا ما تُعيد true لأن الدالة لا تعود حتى يتم قفل semaphore.

## طريقة Semaphore::WaitOne(int) method


يقفل semaphore. ينفذ الانتظار إذا كان ذلك ضروريًا.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| millisecondsTimeout | int | مهلة الانتظار بالمللي ثانية. |

### قيمة الإرجاع

تُعيد true إذا تم قفل semaphore أو false إذا تجاوزت المهلة.

## انظر أيضا

* فئة [Semaphore](../)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)