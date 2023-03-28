---
title: Evaluate()
second_title: Aspose.Slides for C++ API Reference
description: Evaluates the specified XPath expression and returns the typed result.
type: docs
weight: 807
url: /cpp/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate([String](../../../system/string/)) method


Evaluates the specified [XPath](../../) expression and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A string representing an [XPath](../../) expression that can be evaluated. |

### Return Value

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::Evaluate([String](../../../system/string/), [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>) method


Evaluates the specified [XPath](../../) expression and returns the typed result, using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes in the [XPath](../../) expression.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A string representing an [XPath](../../) expression that can be evaluated. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes in the [XPath](../../) expression. |

### Return Value

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::Evaluate([SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\>) method


Evaluates the [XPathExpression](../../xpathexpression/) and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) that can be evaluated. |

### Return Value

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::Evaluate([SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\>, [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\>) method


Uses the supplied context to evaluate the [XPathExpression](../../xpathexpression/), and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) that can be evaluated. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set that the evaluation is to be performed on. |

### Return Value

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
