---
title: WaitAny()
second_title: مرجع API Aspose.Slides للغة C++
description: ينتظر أيًا من المقابض ليتم تفعيله.
type: docs
weight: 14
url: /ar/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) طريقة

ينتظر أيًا من المقابض ليتم تفعيله.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |
| millisecondsTimeout | int | [Timeout](../../timeout/) للانتظار، بالميلي ثانية؛ -1 يعني انتظار لا نهائي، 0 يعني فحص وإرجاع، القيم الإيجابية تمثل مهلات. |

### قيمة الإرجاع

True إذا تم تفعيل أي مقبض، false إذا تجاوزت المهلة.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) طريقة

ينتظر أيًا من المقابض ليتم تفعيله.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) يمثل عدد الميلي ثانية للانتظار، أو [System::TimeSpan](../../../system/timespan/) يمثل -1 ميلي ثانية للانتظار إلى ما لا نهاية. |

### قيمة الإرجاع

True إذا تم تفعيل أي مقبض، false إذا تجاوزت المهلة.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) طريقة

ينتظر أيًا من المقابض ليتم تفعيله.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | المقابض التي ينتظرها. |

### قيمة الإرجاع

True عندما يتلقى كل عنصر في waitHandles إشارة؛ وإلا فإن الطريقة لا تعود أبدًا.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [WaitHandle](../)
* فئة [TimeSpan](../../../system/timespan/)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)