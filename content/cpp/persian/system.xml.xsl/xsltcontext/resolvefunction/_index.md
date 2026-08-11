---
title: ResolveFunction()
second_title: Aspose.Slides برای C++ مرجع API
description: هنگامی که در یک کلاس مشتق شده بازنویسی شود، یک مرجع تابع را حل می‌کند و یک IXsltContextFunction که نمایانگر تابع است را برمی‌گرداند. IXsltContextFunction در زمان اجرا برای دریافت مقدار بازگشتی تابع استفاده می‌شود.
type: docs
weight: 27
url: /fa/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) method


هنگامی که در یک کلاس مشتق شده بازنویسی شود، یک مرجع تابع را حل می‌کند و یک [IXsltContextFunction](../../ixsltcontextfunction/) که نمایانگر تابع است را بر می‌گرداند. [IXsltContextFunction](../../ixsltcontextfunction/) برای دریافت مقدار بازگشتی تابع در زمان اجرا استفاده می‌شود.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | پیشوند تابع همان‌طور که در عبارت [XPath](../../../system.xml.xpath/) ظاهر می‌شود. |
| name | [String](../../../system/string/) | نام تابع. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | آرایه‌ای از انواع آرگومان‌ها برای تابعی که حل می‌شود. این به شما امکان می‌دهد بین متدهایی که نام یکسان دارند (به عنوان مثال متدهای بارگذاری‌شده) انتخاب کنید. |

### مقدار بازگشتی

یک [IXsltContextFunction](../../ixsltcontextfunction/) که نمایانگر تابع است.

## موارد مرتبط

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)