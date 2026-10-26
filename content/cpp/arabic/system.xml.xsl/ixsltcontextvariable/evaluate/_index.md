---
title: Evaluate()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتقييم المتغيّر في وقت التشغيل ويعيد كائنًا يمثل قيمة المتغيّر.
type: docs
weight: 40
url: /ar/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) طريقة

يقوم بتقييم المتغيّر في وقت التشغيل ويعيد كائنًا يمثل قيمة المتغيّر.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```

### المعاملات

| معـامل | نوع | وصف |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | [XsltContext](../../xsltcontext/) تمثّل سياق التنفيذ للمتغيّر. |

### قيمة الإرجاع

[Object](../../../system/object/) تمثّل قيمة المتغيّر. تشمل أنواع الإرجاع الممكنة number, string, [Boolean](../../../system/boolean/), مجزّء مستند، أو مجموعة عقد.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [Object](../../../system/object/)
* الفئة [XsltContext](../../xsltcontext/)
* الفئة [IXsltContextVariable](../)
* النطاق [System::Xml::Xsl](../../)
* المكتبة [Aspose.Slides](../../../)