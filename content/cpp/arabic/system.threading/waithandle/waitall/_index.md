---
title: WaitAll()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينتظر أن تُطلق جميع المقابض.
type: docs
weight: 1
url: /ar/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) طريقة

ينتظر أن تُطلق جميع المقابض.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |
| millisecondsTimeout | int | [Timeout](../../timeout/) للانتظار، بالمللي ثانية؛ -1 يعني انتظار غير نهائي، 0 يعني فحص وإرجاع، القيم الموجبة هي مهلات. |

### قيمة الإرجاع

صحيح إذا تم تشغيل جميع المقابض، خطأ إذا تجاوز المهلة.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) طريقة

ينتظر أن تُطلق جميع المقابض.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) يمثل عدد المللي ثانية للانتظار، أو [System::TimeSpan](../../../system/timespan/) يمثل -1 مللي ثانية للانتظار إلى أجل غير مسمى. |

### قيمة الإرجاع

صحيح إذا تم تشغيل جميع المقابض، خطأ إذا تجاوز المهلة.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) طريقة

ينتظر أن تُطلق جميع المقابض.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |

### قيمة الإرجاع

صحيح عندما يتلقى كل عنصر في waitHandles إشارة؛ وإلا فإن الطريقة لا تُرجع أبداً.

## انظر أيضا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [WaitHandle](../)
* الفئة [TimeSpan](../../../system/timespan/)
* النطاق [System::Threading](../../)
* Library [Aspose.Slides](../../../)