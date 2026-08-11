---
title: ResolveVariable()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق شده بازنویسی می‌شود، یک مرجع متغیر را حل می‌کند و یک IXsltContextVariable که نمایانگر متغیر است را بر می‌گرداند.
type: docs
weight: 14
url: /fa/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) متد

زمانی که در یک کلاس مشتق شده بازنویسی می‌شود، یک مرجع متغیر را حل می‌کند و یک [IXsltContextVariable](../../ixsltcontextvariable/) که نمایانگر متغیر است، بر می‌گرداند.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | پیشوند متغیر همان‌گونه که در عبارت [XPath](../../../system.xml.xpath/) ظاهر می‌شود. |
| name | [String](../../../system/string/) | نام متغیر. |

### مقدار برگشتی

یک [IXsltContextVariable](../../ixsltcontextvariable/) که نمایانگر متغیر در زمان اجرا است.

## موارد مرتبط

* نوع تعریف [SharedPtr](../../../system/sharedptr/)
* کلاس [IXsltContextVariable](../../ixsltcontextvariable/)
* کلاس [String](../../../system/string/)
* کلاس [XsltContext](../)
* فضای‌نام [System::Xml::Xsl](../../)
* کتابخانه [Aspose.Slides](../../../)