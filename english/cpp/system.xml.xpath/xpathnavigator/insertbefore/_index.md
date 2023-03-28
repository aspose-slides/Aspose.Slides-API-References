---
title: InsertBefore()
second_title: Aspose.Slides for C++ API Reference
description: Returns an XmlWriter object used to create a new sibling node before the currently selected node.
type: docs
weight: 911
url: /cpp/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() method


Returns an [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node before the currently selected node.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Return Value

An [XmlWriter](../../../system.xml/xmlwriter/) object used to create a new sibling node before the currently selected node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::InsertBefore([String](../../../system/string/)) method


Creates a new sibling node before the currently selected node using the XML string specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | The XML data string for the new sibling node. |

## See Also

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::InsertBefore([SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>) method


Creates a new sibling node before the currently selected node using the XML contents of the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | An [XmlReader](../../../system.xml/xmlreader/) object positioned on the XML data for the new sibling node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathNavigator::InsertBefore([SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\>) method


Creates a new sibling node before the currently selected node using the nodes in the [XPathNavigator](../) specified.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | An [XPathNavigator](../) object positioned on the node to add as the new sibling node. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
