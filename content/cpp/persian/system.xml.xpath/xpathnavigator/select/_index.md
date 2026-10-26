---
title: Select()
second_title: مرجع API Aspose.Slides برای C++
description: یک مجموعه گره را انتخاب می‌کند، با استفاده از عبارت XPath مشخص‌شده.
type: docs
weight: 794
url: /fa/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) متد

مجموعه‌ای از گره‌ها را انتخاب می‌کند، با استفاده از عبارت [XPath](../../) مشخص‌شده.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | یک [String](../../../system/string/) که نمایانگر یک عبارت [XPath](../../) است. |

### مقدار بازگشتی

یک [XPathNodeIterator](../../xpathnodeiterator/) که به مجموعه گره‌های انتخاب‌شده اشاره می‌کند.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) متد

مجموعه‌ای از گره‌ها را با استفاده از عبارت [XPath](../../) مشخص‌شده و با شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) برای حل پیشوندهای فضای نام انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | یک [String](../../../system/string/) که نمایانگر یک عبارت [XPath](../../) است. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) مورد استفاده برای حل پیشوندهای فضای نام. |

### مقدار بازگشتی

یک [XPathNodeIterator](../../xpathnodeiterator/) که به مجموعه گره‌های انتخاب‌شده اشاره می‌کند.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) متد

مجموعه‌ای از گره‌ها را با استفاده از [XPathExpression](../../xpathexpression/) مشخص‌شده انتخاب می‌کند.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | یک شیء [XPathExpression](../../xpathexpression/) که شامل پرس‌و‌جو [XPath](../../) کامپایل‌شده است. |

### مقدار بازگشتی

یک [XPathNodeIterator](../../xpathnodeiterator/) که به مجموعه گره‌های انتخاب‌شده اشاره می‌کند.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XPathNodeIterator](../../xpathnodeiterator/)
* کلاس [String](../../../system/string/)
* کلاس [XPathNavigator](../)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* کلاس [XPathExpression](../../xpathexpression/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)