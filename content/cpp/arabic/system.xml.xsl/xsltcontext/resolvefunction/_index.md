---
title: ResolveFunction()
second_title: Aspose.Slides للغة C++ مرجع API
description: عند تجاوزها في فئة مشتقة، تحل مرجع الدالة وتعيد IXsltContextFunction يمثل الدالة. يتم استخدام IXsltContextFunction في وقت التنفيذ للحصول على قيمة الإرجاع للدالة.
type: docs
weight: 27
url: /ar/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) طريقة

عند تجاوزها في فئة مشتقة، تحل مرجع الدالة وتعيد [IXsltContextFunction](../../ixsltcontextfunction/) يمثل الدالة. يتم استخدام [IXsltContextFunction](../../ixsltcontextfunction/) في وقت التنفيذ للحصول على قيمة الإرجاع للدالة.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | بادئة الدالة كما تظهر في تعبير [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | اسم الدالة. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | مصفوفة من أنواع المعاملات للدالة التي يتم حلها. يتيح لك ذلك اختيار بين الطرق التي لها نفس الاسم (على سبيل المثال، الطرق المحملة). |

### قيمة الإرجاع

[IXsltContextFunction](../../ixsltcontextfunction/) يمثل الدالة.

## انظر أيضًا

* تعداد [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IXsltContextFunction](../../ixsltcontextfunction/)
* فئة [String](../../../system/string/)
* فئة [XsltContext](../)
* مساحة الاسم [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)