---
title: Handle()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: ينفّذ دالة المعالج على كل استثناء داخلي ويعيد رمي أي استثناءات غير معالجة.
type: docs
weight: 66
url: /ar/system/details_aggregateexception/handle/
---
## التفاصيل_AggregateException::Handle(const Func\<Exception, bool\>\&) طريقة

يقوم بتنفيذ دالة المعالج على كل استثناء داخلي ويعيد رمي أي استثناءات غير معالجة.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | دالة تأخذ استثناءً وتُعيد true إذا تم معالجته. |
## ملاحظات

إذا تم معالجة جميع الاستثناءات، فإن الطريقة تُعيد بشكل طبيعي؛ وإلا، يتم رمي AggregateException جديد يحتوي على الاستثناءات غير المعالجة. 

## انظر أيضًا

* تعريف نوع [Exception](../../exception/)
* فئة [Func](../../func/)
* فئة [Details_AggregateException](../)
* فضاء الأسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)