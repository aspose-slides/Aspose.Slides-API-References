---
title: TryEnter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: محاولة الحصول على قفل حصري للكائن المحدد غير مُنفّذ.
type: docs
weight: 27
url: /ar/system.threading/monitor/tryenter/
---
## Monitor::TryEnter(const SharedPtr\<Object\>\&) طريقة


محاولة الحصول على قفل حصري للكائن المحدد غير مُنفّذ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, bool\&) طريقة


محاولة الحصول على قفل حصري للكائن المحدد، وتقوم بتعيين قيمة بصورة ذرية تشير إلى ما إذا كان القفل قد تم الحصول عليه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Monitor::TryEnter(const SharedPtr\<Object\>\&, int32_t) طريقة


محاولة، للعدد المحدد من المللي ثانية، للحصول على قفل حصري للكائن المحدد غير مُنفّذ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::TryEnter(const SharedPtr\<Object\>\&, TimeSpan) طريقة


محاولة، للمدة المحددة، للحصول على قفل حصري للكائن المحدد غير مُنفّذ.

```cpp
static bool System::Threading::Monitor::TryEnter(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, int32_t, bool\&) طريقة


محاولة، للمدة المحددة، للحصول على قفل حصري للكائن المحدد، وتقوم بتعيين قيمة بصورة ذرية تشير إلى ما إذا كان القفل قد تم الحصول عليه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool &lockTaken)
```

## Monitor::TryEnter(const System::SharedPtr\<Object\>\&, TimeSpan, bool\&) طريقة


محاولة، للمدة المحددة، للحصول على قفل حصري للكائن المحدد، وتقوم بتعيين قيمة بصورة ذرية تشير إلى ما إذا كان القفل قد تم الحصول عليه.

```cpp
static void System::Threading::Monitor::TryEnter(const System::SharedPtr<Object> &obj, TimeSpan timeout, bool &lockTaken)
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Monitor](../)
* فئة [TimeSpan](../../../system/timespan/)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)