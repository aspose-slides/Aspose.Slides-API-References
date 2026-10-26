---
title: Evaluate()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقيم التعبير XPath المحدد ويعيد النتيجة المكتوبة.
type: docs
weight: 807
url: /ar/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) الطريقة

يقيم التعبير [XPath](../../) المحدد ويعيد النتيجة المكتوبة.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | سلسلة تمثل تعبير [XPath](../../) يمكن تقييمه. |

### قيمة الإرجاع

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) الطريقة

يقيم التعبير [XPath](../../) المحدد ويعيد النتيجة المكتوبة، باستخدام الكائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المحدد لحل بادئات الفضاء الاسمي في التعبير [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | سلسلة تمثل تعبير [XPath](../../) يمكن تقييمه. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | الكائن [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) المستخدم لحل بادئات الفضاء الاسمي في تعبير [XPath](../../). |

### قيمة الإرجاع

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) الطريقة

يقيم [XPathExpression](../../xpathexpression/) ويعيد النتيجة المكتوبة.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) يمكن تقييمه. |

### قيمة الإرجاع

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) الطريقة

يستخدم السياق المقدم لتقييم [XPathExpression](../../xpathexpression/) ويعيد النتيجة المكتوبة.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) يمكن تقييمه. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | [XPathNodeIterator](../../xpathnodeiterator/) الذي يشير إلى مجموعة العقد المحددة التي يتم إجراء التقييم عليها. |

### قيمة الإرجاع

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [String](../../../system/string/)
* فئة [XPathNavigator](../)
* فئة [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فئة [XPathExpression](../../xpathexpression/)
* فئة [XPathNodeIterator](../../xpathnodeiterator/)
* نطاق [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)