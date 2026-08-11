---
title: SelectSingleNode()
second_title: مرجع API Aspose.Slides برای C++
description: یک گرهٔ منفرد را در XPathNavigator با استفاده از پرس‌و‌جوی XPath مشخص‌شده انتخاب می‌کند.
type: docs
weight: 781
url: /fa/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) method

یک گرهٔ تک را در [XPathNavigator](../) با استفاده از پرس‌و‌جوی [XPath](../../) مشخص‌شده انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | یک [String](../../../system/string/) که نمایانگر یک عبارت [XPath](../../) است. |

### مقدار بازگشتی

یک شیء [XPathNavigator](../) که شامل اولین گرهٔ مطابق برای پرس‌و‌جوی [XPath](../../) مشخص‌شده است؛ در غیر این صورت **nullptr** اگر هیچ نتیجه‌ای وجود نداشت.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method

یک گرهٔ تک را در شیء [XPathNavigator](../) با استفاده از پرس‌و‌جوی [XPath](../../) مشخص‌شده و با شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) برای رفع پیشوندهای فضای نام انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | یک [String](../../../system/string/) که نمایانگر یک عبارت [XPath](../../) است. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) که برای رفع پیشوندهای فضای نام در پرس‌و‌جوی [XPath](../../) استفاده می‌شود. |

### مقدار بازگشتی

یک شیء [XPathNavigator](../) که شامل اولین گرهٔ مطابق برای پرس‌و‌جوی [XPath](../../) مشخص‌شده است؛ در غیر این صورت **nullptr** اگر هیچ نتیجه‌ای وجود نداشت.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method

یک گرهٔ تک را در [XPathNavigator](../) با استفاده از شیء [XPathExpression](../../xpathexpression/) مشخص‌شده انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | یک شیء [XPathExpression](../../xpathexpression/) که شامل پرس‌و‌جوی [XPath](../../) کامپایل‌شده است. |

### مقدار بازگشتی

یک شیء [XPathNavigator](../) که شامل اولین گرهٔ مطابق برای پرس‌و‌جوی [XPath](../../) مشخص‌شده است؛ در غیر این صورت **nullptr** اگر هیچ نتیجه‌ای وجود نداشت.

## مراجع مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)