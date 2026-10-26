---
title: Invoke()
second_title: Aspose.Slides لـ C++ مرجع API
description: توفر الطريقة لاستدعاء الدالة مع المعلمات المحددة في السياق المحدد.
type: docs
weight: 53
url: /ar/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) طريقة

توفر الطريقة لاستدعاء الدالة مع المعلمات المحددة في السياق المحدد.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | سياق XSLT لاستدعاء الدالة. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | معلمات استدعاء الدالة. كل معلمة هي عنصر في المصفوفة. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | عقدة السياق لاستدعاء الدالة. |

### قيمة الإرجاع

كائن [Object](../../../system/object/) يمثل قيمة الإرجاع للدالة.

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Object](../../../system/object/)
* فئة [XsltContext](../../xsltcontext/)
* فئة [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* فئة [IXsltContextFunction](../)
* نطاق [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)