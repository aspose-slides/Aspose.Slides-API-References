---
title: Select()
second_title: Aspose.Slides for C++ API Reference
description: Selects a node set, using the specified XPath expression.
type: docs
weight: 794
url: /system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) method


Selects a node set, using the specified [XPath](../../) expression.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) pointing to the selected node set.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selects a node set using the specified [XPath](../../) expression with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method


Selects a node set using the specified [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) query. |

### Return Value

An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)