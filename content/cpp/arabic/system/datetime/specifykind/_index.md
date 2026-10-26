---
title: SpecifyKind()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائن DateTime جديدًا يمثل نفس عدد الـ ticks كما في كائن DateTime المحدد ويمثل الوقت المحلي أو وقت UTC أو لا شيء حسب ما يحدده الوسيط kind.
type: docs
weight: 833
url: /ar/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) طريقة

ينشئ كائنًا جديدًا من نوع [DateTime](../) يمثل نفس عدد الـ ticks كما في كائن [DateTime](../) المحدد ويمثل الوقت المحلي أو وقت UTC أو لا شيء حسب ما يحدده الوسيط **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [DateTime](../) | الكائن [DateTime](../) لنسخ عدد الـ ticks منه |
| kind | [DateTimeKind](../../datetimekind/) | يحدد ما إذا كان الكائن الجديد يجب أن يمثل الوقت المحلي أو وقت UTC أو لا شيء |

### قيمة الإرجاع

كائن [DateTime](../) جديد يمثل نفس عدد الـ ticks مثل **value** وقيمة DateTimeKind المحددة بواسطة **kind**.

## انظر أيضًا

* عدد [DateTimeKind](../../datetimekind/)
* صنف [DateTime](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)