---
title: Enter()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستحوذ على قفل حصري لكائن محدد.
type: docs
weight: 1
url: /ar/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) طريقة

يستحوذ على قفل حصري لكائن محدد.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الكائن الذي يجب الحصول على قفل المراقبة له. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) طريقة

يستحوذ على قفل حصري للكائن المحدد، ويضبط قيمةً بشكل ذري تُظهر ما إذا تم الحصول على القفل.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Monitor](../)
* نطاق [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)