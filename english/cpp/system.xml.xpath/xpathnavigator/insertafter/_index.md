---
title: InsertAfter()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlWriter object used to create a new sibling node after the currently selected node.
type: docs
weight: 898
url: /cpp/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() method


Returns an [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### Return Value

An [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node.

## XPathNavigator::InsertAfter(String) method


Creates a new sibling node after the currently selected node using the XML string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | The XML data string for the new sibling node. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) method


Creates a new sibling node after the currently selected node using the XML contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new sibling node. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) method


Creates a new sibling node after the currently selected node using the nodes in the [XPathNavigator](../) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | An [XPathNavigator](../) object positioned on the node to add as the new sibling node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)