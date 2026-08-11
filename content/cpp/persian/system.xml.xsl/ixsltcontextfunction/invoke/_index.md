---
title: Invoke()
second_title: مرجع API Aspose.Slides برای C++
description: روشی را برای صدا زدن تابع با آرگومان‌های داده‌شده در زمینه‌ی داده‌شده فراهم می‌کند.
type: docs
weight: 53
url: /fa/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) method

این متد را برای صدا زدن تابع با آرگومان‌های داده‌شده در زمینه‌ی داده‌شده فراهم می‌کند.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | زمینه XSLT برای فراخوانی تابع. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | آرگومان‌های فراخوانی تابع. هر آرگومان یک عنصر در آرایه است. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | گرهٔ زمینه برای فراخوانی تابع. |

### مقدار بازگشت

یک [Object](../../../system/object/) که مقدار بازگشت تابع را نشان می‌دهد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)