---
title: WaitOne()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينتظر أن يُطلق المقبض لفترة غير محدودة.
type: docs
weight: 27
url: /ar/system.threading/waithandle/waitone/
---
## طريقة WaitHandle::WaitOne() method

ينتظر أن يُطلق المقبض لفترة غير محدودة.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### قيمة الإرجاع

دائمًا يُعيد true لأنه لا يحدث انتهاء مهلة.

## طريقة WaitHandle::WaitOne(int) method

ينتظر أن يُطلق المقبض.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) للانتظار، بالمللي ثانية؛ -1 يعني انتظار لا نهائي، 0 يعني فحص وإرجاع، القيم الإيجابية هي مهلات. |

### قيمة الإرجاع

True إذا تم إطلاق المقبض، false إذا تجاوزت المهلة.

## طريقة WaitHandle::WaitOne(TimeSpan) method

ينتظر أن يُطلق المقبض.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) يمثل عدد المللي ثانية للانتظار، أو [System::TimeSpan](../../../system/timespan/) يمثل -1 مللي ثانية للانتظار إلى أجل غير مسمى. |

### قيمة الإرجاع

True إذا تم إطلاق المقبض، false إذا تجاوزت المهلة.

## طريقة WaitHandle::WaitOne(int, bool) method

ينتظر أن يُطلق المقبض.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) للانتظار، بالمللي ثانية؛ -1 يعني انتظار لا نهائي، 0 يعني فحص وإرجاع، القيم الإيجابية هي مهلات. |
| exitContext | **bool** | إذا كان true، يجب على الانتظار تحرير القفل عن المقبض قبل الانتظار له. |

### قيمة الإرجاع

True إذا تم إطلاق المقبض، false إذا تجاوزت المهلة.

## انظر أيضًا

* الفئة [WaitHandle](../)
* الفئة [TimeSpan](../../../system/timespan/)
* مساحة الاسم [System::Threading](../../)
* المكتبة [Aspose.Slides](../../../)