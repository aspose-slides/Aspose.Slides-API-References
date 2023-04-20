---
title: AppendChild()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlWriter object used to create one or more new child nodes at the end of the list of child nodes of the current node.
type: docs
weight: 885
url: /cpp/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() method


Returns an [XmlWriter](../../../system.xml/xmlwriter/) object used to create one or more new child nodes at the end of the list of child nodes of the current node.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### Return Value

An [XmlWriter](../../../system.xml/xmlwriter/) object used to create new child nodes at the end of the list of child nodes of the current node.

## XPathNavigator::AppendChild(String) method


Creates a new child node at the end of the list of child nodes of the current node using the XML data string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | The XML data string for the new child node. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) method


Creates a new child node at the end of the list of child nodes of the current node using the XML contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new child node. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) method


Creates a new child node at the end of the list of child nodes of the current node using the nodes in the [XPathNavigator](../) specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | An [XPathNavigator](../) object positioned on the node to add as the new child node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)