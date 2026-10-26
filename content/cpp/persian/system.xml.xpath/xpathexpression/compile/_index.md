---
title: Compile()
second_title: Aspose.Slides برای C++ مرجع API
description: عبارت XPath مشخص شده را کامپایل می‌کند و شیء XPathExpression که نمایانگر عبارت XPath است را بازمی‌گرداند.
type: docs
weight: 66
url: /fa/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String&) متد

عبارت [XPath](../../) مشخص شده را کامپایل می‌کند و یک شیء [XPathExpression](../) که نمایانگر عبارت [XPath](../../) است را برمی‌گرداند.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارتی از نوع [XPath](../../). |

### مقدار بازگشت

شیء [XPathExpression](../).

## XPathExpression::Compile(const String&, const SharedPtr\<IXmlNamespaceResolver\>\&) متد

عبارت [XPath](../../) مشخص شده را کامپایل می‌کند، با شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) که برای حل‌نام‌فضا تعیین شده است، و یک شیء [XPathExpression](../) که نمایانگر عبارت [XPath](../../) است را برمی‌گرداند.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | عبارتی از نوع [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | شیئ‌ای که رابط [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) را برای حل‌نام‌فضا پیاده‌سازی می‌کند. |

### مقدار بازگشت

شیء [XPathExpression](../).

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathExpression](../)
* کلاس [String](../../../system/string/)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)