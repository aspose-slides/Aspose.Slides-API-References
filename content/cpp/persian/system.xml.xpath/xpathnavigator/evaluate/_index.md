---
title: Evaluate()
second_title: Aspose.Slides برای مرجع API C++
description: عبارت XPath مشخص‌شده را ارزیابی می‌کند و نتیجهٔ تایپ‌شده را برمی‌گرداند.
type: docs
weight: 807
url: /fa/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) متد


عبارت [XPath](../../) مشخص شده را ارزیابی می‌کند و نتیجهٔ تایپ‌شده را برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | رشته‌ای که نمایانگر عبارت [XPath](../../) است و می‌تواند ارزیابی شود. |

### مقدار بازگشت

نتیجهٔ عبارت ([Boolean](../../../system/boolean/)، عدد، رشته یا مجموعهٔ گره). این به‌صورت متوالی به اشیای [Boolean](../../../system/boolean/)، [Double](../../../system/double/)، [String](../../../system/string/) یا [XPathNodeIterator](../../xpathnodeiterator/) نسبت داده می‌شود.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) متد


عبارت [XPath](../../) مشخص شده را ارزیابی می‌کند و نتیجهٔ تایپ‌شده را برمی‌گرداند، با استفاده از شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) مشخص‌شده برای حل پیشوندهای فضای نام در عبارت [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | رشته‌ای که نمایانگر عبارت [XPath](../../) است و می‌تواند ارزیابی شود. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | شیء [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) مورد استفاده برای حل پیشوندهای فضای نام در عبارت [XPath](../../). |

### مقدار بازگشت

نتیجهٔ عبارت ([Boolean](../../../system/boolean/)، عدد، رشته یا مجموعهٔ گره). این به‌صورت متوالی به اشیای [Boolean](../../../system/boolean/)، [Double](../../../system/double/)، [String](../../../system/string/) یا [XPathNodeIterator](../../xpathnodeiterator/) نسبت داده می‌شود.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) متد


[XPathExpression](../../xpathexpression/) را ارزیابی می‌کند و نتیجهٔ تایپ‌شده را برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/)ی که می‌توان آن را ارزیابی کرد. |

### مقدار بازگشت

نتیجهٔ عبارت ([Boolean](../../../system/boolean/)، عدد، رشته یا مجموعهٔ گره). این به‌صورت متوالی به اشیای [Boolean](../../../system/boolean/)، [Double](../../../system/double/)، [String](../../../system/string/) یا [XPathNodeIterator](../../xpathnodeiterator/) نسبت داده می‌شود.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) متد


از زمینهٔ ارائه‌شده برای ارزیابی [XPathExpression](../../xpathexpression/) استفاده می‌کند و نتیجهٔ تایپ‌شده را برمی‌گرداند.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/)ی که می‌توان آن را ارزیابی کرد. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | [XPathNodeIterator](../../xpathnodeiterator/)ی که به مجموعهٔ گرهٔ انتخاب‌شده‌ای که ارزیابی بر روی آن انجام می‌شود، اشاره دارد. |

### مقدار بازگشت

نتیجهٔ عبارت ([Boolean](../../../system/boolean/)، عدد، رشته یا مجموعهٔ گره). این به‌صورت متوالی به اشیای [Boolean](../../../system/boolean/)، [Double](../../../system/double/)، [String](../../../system/string/) یا [XPathNodeIterator](../../xpathnodeiterator/) نسبت داده می‌شود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [String](../../../system/string/)
* کلاس [XPathNavigator](../)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* کلاس [XPathExpression](../../xpathexpression/)
* کلاس [XPathNodeIterator](../../xpathnodeiterator/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)