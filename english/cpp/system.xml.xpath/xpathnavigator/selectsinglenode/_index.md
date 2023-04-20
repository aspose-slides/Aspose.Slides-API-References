---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API Reference
description: Selects a single node in the XPathNavigator using the specified XPath query.
type: docs
weight: 781
url: /cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) method


Selects a single node in the [XPathNavigator](../) using the specified [XPath](../../) query.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |

### Return Value

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise, **nullptr** if there are no query results.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selects a single node in the [XPathNavigator](../) object using the specified [XPath](../../) query with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | A [String](../../../system/string/) representing an [XPath](../../) expression. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes in the [XPath](../../) query. |

### Return Value

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise **nullptr** if there are no query results.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Selects a single node in the [XPathNavigator](../) using the specified [XPathExpression](../../xpathexpression/) object.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) query. |

### Return Value

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise **nullptr** if there are no query results.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)