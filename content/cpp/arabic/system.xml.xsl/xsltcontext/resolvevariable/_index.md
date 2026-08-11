---
title: ResolveVariable()
second_title: Aspose.Slides لـ C++ مرجع API
description: عند تجاوزها في فئة مشتقة، تقوم بحل إشارة المتغير وتُعيد IXsltContextVariable تمثل المتغير.
type: docs
weight: 14
url: /ar/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) طريقة


عند تجاوزها في فئة مشتقة، تقوم بحل إشارة المتغير وتُعيد [IXsltContextVariable](../../ixsltcontextvariable/) تمثل المتغير.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | بادئة المتغير كما تظهر في تعبير [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | اسم المتغير. |

### قيمة الإرجاع

[IXsltContextVariable](../../ixsltcontextvariable/) تمثل المتغير أثناء وقت التشغيل.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IXsltContextVariable](../../ixsltcontextvariable/)
* فئة [String](../../../system/string/)
* فئة [XsltContext](../)
* مساحة الأسماء [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)